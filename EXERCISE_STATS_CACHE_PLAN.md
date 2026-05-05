# Exercise Stats Cache Plan

Future feature: persist exercise stats across app sessions so library detail pages, workout creation, and stats modals can share the same local history data.

## Goals

- Cache exercise stats by exercise group ID.
- Populate the cache when viewing an exercise detail page or adding an exercise to a workout.
- Use cached stats to show quick values like `Last Max Wt.` without repeated API calls.
- Allow manual refresh from Settings.
- Allow clearing the cache from Settings.

## Suggested Cache File

Store a server-side JSON file, for example:

```text
data/exercise_stats_cache.json
```

Suggested shape:

```json
{
  "12345": {
    "fetched_at": "2026-05-04T18:22:00Z",
    "data": {
      "status": "success",
      "data": [
        {
          "dayStr": "2026-05-01",
          "oneRepMax": 42.5,
          "maxWeight": 32.5,
          "totalCapacity": 2100
        }
      ]
    }
  }
}
```

## Endpoint Ideas

- `GET /api/stats_cached/<group_id>`
  - Return cached stats when present.
  - Fetch live stats, cache them, and return them when missing.

- `GET /api/stats/<group_id>?refresh=1`
  - Fetch live stats from Speediance.
  - Update the cache entry.
  - Return fresh stats.

- `POST /api/stats_cache/clear`
  - Delete or empty the cache file.

- `POST /api/stats_cache/refresh_cached`
  - Refresh only group IDs already present in the cache.
  - Do not refresh the full exercise library in the first version.

## Refresh Strategy

Refresh cached group IDs in batches with pauses between calls to reduce risk of API throttling or server issues.

Initial defaults:

- Refresh one exercise at a time.
- Wait about 1 second between calls.
- Stop on unauthorized errors.
- Report progress in Settings.

For progress, a streaming response would be ideal:

```text
Refreshing 1/38: 12345
Refreshing 2/38: 67890
Done
```

## UI Behavior

- `create.html` can use cached stats to show `Last Max Wt.` after the cable position chip.
- `exercise_detail.html` can refresh/populate cache when the page loads stats.
- `View Stats` should refresh the cache for that exercise.
- Settings can show cache count and last refresh time later.

## First Step Before Disk Cache

The current lightweight version should use a page-session JavaScript cache only. If performance or repeated API calls become a real problem, implement this disk cache plan.
