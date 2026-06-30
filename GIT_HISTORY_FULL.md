# Full Git History & Time Log
Generated: 2026-03-26
Projects: UnofficialSpeedianceWorkoutManager · Claude Smart Gym Coach

---

## Table of Contents
1. [Summary](#summary)
2. [2025 — Upstream Origin (Pre-Fork)](#2025--upstream-origin-pre-fork)
3. [2026 — Your Work (ANPC86)](#2026--your-work-anpc86)
4. [Reflog: Raw Git Session Evidence](#reflog-raw-git-session-evidence)
5. [Hours Estimate](#hours-estimate)
6. [Smart Gym Coach Full Log](#smart-gym-coach-full-log)
7. [Notes on Methodology](#notes-on-methodology)

---

## Summary

| Project | Repo | First Commit | Your Commits | Active Days | Est. Hours |
|---|---|---|---|---|---|
| UnofficialSpeedianceWorkoutManager | ANPC86/UnofficialSpeedianceWorkoutManager | 2026-02-15 (your fork) | 43 | 12 | 19–33 hrs |
| Claude Smart Gym Coach | ANPC86/claude-smart-gym-coach | 2026-03-21 | 7 | 2 | 3.5–6 hrs |
| **Total (your work)** | | **2026-02-15** | **50** | **14** | **~22–39 hrs** |

> Note: The Speediance repo contains 88 total commits. 45 are from upstream/other contributors (2025 work by hbui3, thinkle, benengele). Your 43 commits all fall in 2026.

---

## 2025 — Upstream Origin (Pre-Fork)

These commits exist in your repo's history because you forked from hbui3's project. You did **not** write this code, but it forms the base you built on. It is included here for completeness and context.

**Author:** hbui3 (Hendrik Buisker) — `hendrik@buisker.com`
**Other contributors:** Benjamin Engele, Tom Hinkle

### What the upstream project was when you forked it (Dec 2025 state)

| Date | Time (UTC+1) | Author | Commit Message |
|---|---|---|---|
| 2025-12-15 | 12:58 | hbui3 | Update documentation and add experimental AI features |
| 2025-12-15 | 13:31 | hbui3 | Initial commit with AI features and build action |
| 2025-12-15 | 13:37 | hbui3 | Add .gitkeep to track static folder |
| 2025-12-15 | 13:50 | hbui3 | Add auto-upload to release in build workflow |
| 2025-12-15 | 13:54 | hbui3 | Add GUI wrapper for server logs and control |
| 2025-12-15 | 14:01 | hbui3 | Rename to Unofficial Speediance Workout Manager |
| 2025-12-15 | 14:04 | hbui3 | Update README with exe usage instructions |
| 2025-12-15 | 14:11 | hbui3 | Update text in create.html |
| 2025-12-15 | 14:17 | hbui3 | Update weight limits: 100kg double rope, 50kg single rope |
| 2025-12-15 | 14:19 | hbui3 | Update min weight limits: 7kg double, 4kg single |
| 2025-12-15 | 14:27 | hbui3 | Add unit switching (Metric/Imperial) support |
| 2025-12-15 | 15:07 | hbui3 | Update unit conversion to 2.2, fix UI labels, and update documentation |
| 2025-12-15 | 15:13 | hbui3 | Add Buy Me a Coffee button to footer |
| 2025-12-15 | 15:15 | hbui3 | Move Buy Me a Coffee button to top banner |
| 2025-12-15 | 15:17 | hbui3 | Move Buy Me a Coffee button to top slim banner |
| 2025-12-15 | 15:19 | hbui3 | Update README for v0.8 release |
| 2025-12-15 | 15:20 | hbui3 | Remove What's New section from README |
| 2025-12-15 | 15:24 | hbui3 | Add Security & Privacy section and Region note to README |
| 2025-12-15 | 15:38 | hbui3 | Exclude API docs from repository |
| 2025-12-15 | 16:07 | hbui3 | Update license from Creative Commons to MIT |
| 2025-12-15 | 16:34 | hbui3 | Add feature images to README |
| 2025-12-16 | 08:23 | hbui3 | Add Mac build to CI and update README instructions |
| 2025-12-16 | 08:24 | hbui3 | Resolve merge conflict in README |
| 2025-12-16 | 08:32 | hbui3 | Fix duplicate key in build.yml |
| 2025-12-16 | 08:39 | hbui3 | feat: improve login error reporting with debug info |
| 2025-12-16 | 08:46 | hbui3 | ci: trigger build on push to main and upload mac artifacts |
| 2025-12-16 | 08:47 | hbui3 | ci: revert build trigger to release only |
| 2025-12-16 | 08:56 | hbui3 | ci: update build workflow to run on release publish |
| 2025-12-18 | 17:34 | hbui3 | Implement debug features, improve error handling, and enhance UI for AI features |
| 2025-12-18 | 17:41 | hbui3 | Update README with AI features, Export JSON, and Debugging tools |
| 2025-12-18 | 17:47 | hbui3 | Implement disk-based library caching for faster startup |
| 2025-12-18 | 18:42 | hbui3 | Add exercise categories, filtering, and persistent AI prompt settings |
| 2025-12-18 | 21:56 | hbui3 | Add Training Calendar feature with drag-and-drop scheduling |
| 2025-12-19 | 07:44 | hbui3 | Add auto-scroll to calendar on drag and update README about login expiration |
| 2025-12-19 | 08:06 | hbui3 | Update README to modify screenshots section |
| 2025-12-28 | 14:57 | Benjamin Engele | Import and export presets for exercises |
| 2025-12-28 | 16:16 | Benjamin Engele | Generate prompt with preset information and support for RM values |
| 2025-12-29 | 08:44 | Tom Hinkle | Add support for Gym Pal |
| 2025-12-31 | 09:07 | hbui3 | Merge pull request #6 from benengele/main |
| 2025-12-31 | 09:12 | hbui3 | Merge pull request #8 from thinkle/main |

**Upstream 2025 total:** 40 commits across 5 active days (Dec 15, 16, 18, 19, 28–31)

### What you inherited when you forked (Dec 2025 feature set)

- Python Flask web app for Speediance gym equipment
- Workout library browser with AI prompt generation
- Training calendar with drag-and-drop
- Exercise categories and filtering
- Library disk caching
- GUI wrapper for server
- Metric/Imperial unit switching
- CI/CD build pipeline (Windows .exe + Mac)
- Preset import/export (benengele contribution)
- Gym Pal integration (thinkle contribution)

---

## 2026 — Your Work (ANPC86)

All timestamps in Mountain Time (MST/MDT, UTC-7).

### 2026-02-15 — Session 1: Workout History Feature
**3 commits · Est. 1.5–2.5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 18:02 | Add workout history feature with timezone support | First feature: new page pulling workout history from API |
| 18:58 | Reorganize main page layout and sort workouts | Re-layout of index.html |
| 19:17 | Add file download features for workout history exports | JSON/CSV export from history |

---

### 2026-02-16 — Session 2: Calendar + Builder Polish
**2 commits · Est. 1–2 hrs**

| Time | Commit | Notes |
|---|---|---|
| 20:55 | Add monthly calendar view to workout history page | Calendar heatmap on history page |
| 22:22 | Add clipboard fallback and cable position display for workout builder | UX improvements |

---

### 2026-02-17 — Session 3: Merge & Bug Fix
**2 commits · Est. 0.5–1.5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 13:33 | Fix save workout crash when preset_id or set values are null | Critical crash fix |
| 13:33 | Merge branch 'feature/add-workout-history' into qa/combined | Merge into QA |

---

### 2026-02-21 — Session 4: Major Builder Day (earliest 07:23)
**7 commits · Est. 3–5 hrs** · Earliest activity: 07:23 MST

| Time | Commit | Notes |
|---|---|---|
| 07:23 | Fix cardio time input and dynamic preset dropdown in workout builder | (appears twice — branch + qa merge) |
| 07:57 | Fix Customize dropdown label to show LBS for Imperial users | (appears twice — branch + qa merge) |
| 08:05 | Fix Temporal Dead Zone crash: move userUnit declaration before PRESET_LABELS | (appears twice) |
| 08:12 | Condense workout card stats into single line | Visual polish |

> Note: Duplicate commits result from the feature-branch-then-merge-to-qa workflow.

---

### 2026-02-22 — Session 5: Vita + Debug Console (earliest 15:34)
**7 commits · Est. 3–5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 15:34 | Add API debug console feature | New Blueprint: debug_routes.py |
| 15:35 | Merge feature/debug-console into qa/combined | |
| 16:15 | Add completionMethod-aware goal unit rendering in workout builder | completionMethod logic |
| 17:14 | Handle Vita exercises (dataStatType=6) in builder and save | Vita support: level 1-10, weights="0" |
| 17:16 | Merge feature/workout-builder-improvements into qa/combined | |
| 17:46 | Add move-to-top and move-to-bottom buttons to exercise cards | UX feature |
| 17:46 | Merge branch 'feature/workout-builder-improvements' into qa/combined | |

---

### 2026-02-23 — Session 6: Workout Count + GroupId Fix
**4 commits · Est. 1.5–2.5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 22:00 | Fix groupId stored as string in addExerciseToPlan | Bug: parseInt missing |
| 22:00 | Merge branch 'feature/workout-builder-improvements' into qa/combined | |
| 22:03 | Add workout count to My Workouts heading on index page | (appears twice: branch + cherry-pick) |

---

### 2026-02-24 — No Commits (Branch Switching Only)
Reflog shows activity at 23:32–23:33 MST (checkout between branches). Likely exploring or testing. No code committed.

---

### 2026-02-26 — Session 7: Live Stats Bar (earliest 23:09 → committed 23:30)
**2 commits · Est. 1.5–2.5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 23:30 | Add live workout stats bar to builder (exercises, volume, time, rest) | calculateWorkoutStats() |
| 23:31 | Merge branch 'feature/workout-builder-improvements' into qa/combined | |

> Reflog note: Branch was checked out at 23:09, commit at 23:30. ~20+ min of active coding visible.

---

### 2026-02-27 — Session 8: Radar Chart + Header Redesign + Upstream Merge
**5 commits · Est. 2–4 hrs**

| Time | Commit | Notes |
|---|---|---|
| 20:58 | Add Est Burn stat chip and Target Muscles radar chart to workout builder | Chart.js radar chart |
| 20:59 | Merge branch 'feature/workout-builder-improvements' into qa/combined | |
| 21:08 | Redesign workout builder header: two-row layout with right-aligned stats | Header layout overhaul |
| 21:09 | Merge branch 'feature/workout-builder-improvements' into qa/combined | |
| 23:23 | Merge upstream/main (v1.1) — preserve all fork customizations | Upstream sync |

---

### 2026-03-02 — Session 9: Timezone Fix + Upstream v1.2
**2 commits · Est. 1–2 hrs**

| Time | Commit | Notes |
|---|---|---|
| 15:54 | Merge upstream/main (v1.2) — preserve all fork customizations | Upstream sync |
| 17:43 | Fix calendar day offset (timezone) and move instructions below calendar | Timezone bug in calendar |

> Reflog shows a separate branch `merge/upstream-v1.2` was created for the merge, checked out at 14:24.

---

### 2026-03-20 — Session 10: README + LBS Fix (Go-Public Prep)
**4 commits · Est. 1.5–2.5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 21:57 | Fix LBS/KG weight unit handling: no conversion in Python or JS import | LBS bug fix before going public |
| 22:01 | Add fork attribution and preserve original dev's discontinuation notice | Credit hbui3 |
| 22:03 | Merge branch 'qa/combined' | Final merge to main |
| 22:06 | Add fork changes and features section to README | Documenting your additions |

---

### 2026-03-21 — Session 11: Docker Setup
**3 commits · Est. 1–2 hrs**

| Time | Commit | Notes |
|---|---|---|
| 16:13 | Add docker-compose template | First Docker support |
| 16:15 | Add volume path comment to docker-compose | |
| 16:15 | Add Docker setup instructions to README | |

---

### 2026-03-25 — Session 12: Limits + Headers Fix
**2 commits · Est. 0.5–1.5 hrs**

| Time | Commit | Notes |
|---|---|---|
| 21:53 | Add header to _get_headers() for compatibility removed redundant overrides | API compatibility fix |
| 22:04 | Show workout and exercise limits enforced by Speediance app | Display limits in UI |

---

## Reflog: Raw Git Session Evidence

The git reflog captures every branch checkout, merge, reset, and stash — not just commits. This is more granular than the commit log and reveals working session boundaries.

Selected reflog entries showing session activity (Speediance repo, your operations only):

```
2026-03-25 21:53  pull origin main --rebase (start)
2026-03-25 21:53  commit: Add header to _get_headers()
2026-03-25 22:04  commit: Show workout and exercise limits
2026-03-25 22:05  checkout: qa/combined → main (merge + done)

2026-03-20 21:57  checkout: merge/upstream-v1.2 → qa/combined
2026-03-20 21:57  commit: Fix LBS/KG weight unit handling
2026-03-20 22:00  checkout: qa/combined → main
2026-03-20 22:01  commit: Add fork attribution
2026-03-20 22:03  merge qa/combined
2026-03-20 22:06  commit: Add fork changes section to README

2026-03-02 14:24  checkout: merge/upstream-v1.1 → merge/upstream-v1.2
2026-03-02 15:54  commit (merge): Merge upstream/main v1.2
2026-03-02 17:43  commit: Fix calendar day offset

2026-02-27 20:58  checkout: qa/combined → feature/workout-builder-improvements
2026-02-27 20:58  commit: Add Est Burn + radar chart
2026-02-27 21:00  checkout back to qa/combined
2026-02-27 21:08  checkout: qa/combined → feature/workout-builder-improvements
2026-02-27 21:08  commit: Redesign workout builder header
2026-02-27 21:09  merge into qa/combined
2026-02-27 21:18  checkout: qa/combined → merge/upstream-v1.1
2026-02-27 23:23  commit (merge): Merge upstream/main v1.1

2026-02-26 23:09  checkout: qa/combined → feature/workout-builder-improvements
2026-02-26 23:30  commit: Add live workout stats bar
2026-02-26 23:31  checkout back + merge into qa/combined
2026-02-26 23:38  stash created (GitHub Desktop auto-stash)
2026-02-26 23:39  checkout: qa/combined → feature/workout-builder-improvements

2026-02-24 23:32  checkout: feature/workout-builder-improvements → qa/combined
2026-02-24 23:33  checkout: qa/combined → feature/workout-builder-improvements (short browse)

2026-02-23 22:00  checkout: qa/combined → feature/workout-builder-improvements
2026-02-23 22:00  commit: Fix groupId
2026-02-23 22:00  merge into qa/combined
2026-02-23 22:03  commit: Add workout count
2026-02-23 22:09  cherry-pick: workout count onto feature branch

2026-02-22 15:34  commit: Add API debug console
2026-02-22 15:35  Merge debug-console into qa/combined
2026-02-22 16:15  commit: completionMethod-aware rendering
2026-02-22 17:14  commit: Handle Vita exercises
2026-02-22 17:15  checkout → qa/combined
2026-02-22 17:45  checkout: qa/combined → feature/workout-builder-improvements
2026-02-22 17:46  commit: move-to-top/bottom buttons
2026-02-22 17:46  merge into qa/combined
```

**Active stashes found (GitHub Desktop auto-saves):**
- `stash@{0}` — feature/workout-builder-improvements (work in progress)
- `stash@{1}` — qa/combined
- `stash@{2}` — adjust-main-page-layout
- `stash@{3}` — feature/add-workout-history

> These stashes indicate at least 4 additional branches where work was in progress but interrupted. GitHub Desktop auto-stashes on branch switch.

---

## Hours Estimate

### Method
- Each "session" day is examined using reflog timestamps to find start and end of activity.
- Heavy days with many commits and long reflog spans get higher estimates.
- Does NOT include: reading docs, testing on QA NAS, Claude conversations, waiting for deployments.

### Per-Session Table (Speediance Workout Manager)

| Date | Your Commits | Earliest Activity | Latest Activity | Span | Est. Hours |
|---|---|---|---|---|---|
| Feb 15 | 3 | 18:02 | 19:17 | 1h 15m | 1.5–2.5 |
| Feb 16 | 2 | 20:55 | 22:22 | 1h 27m | 1–2 |
| Feb 17 | 2 | 13:33 | 13:33 | ~0m (merges) | 0.5–1 |
| Feb 21 | 7 | 07:23 | 08:12 | 49m logged | 3–5* |
| Feb 22 | 7 | 15:34 | 17:46 | 2h 12m | 3–5* |
| Feb 23 | 4 | 22:00 | 22:09 | 9m logged | 1.5–2.5* |
| Feb 24 | 0 | 23:32 | 23:33 | 1m (browse) | 0 |
| Feb 26 | 2 | 23:09 | 23:39 | 30m logged | 1.5–2.5* |
| Feb 27 | 5 | 20:58 | 23:23 | 2h 25m | 2–4 |
| Mar 2 | 2 | 14:24 | 17:43 | 3h 19m span | 1–2 |
| Mar 20 | 4 | 21:57 | 22:06 | 9m logged | 1.5–2.5* |
| Mar 21 | 3 | 16:13 | 16:15 | 2m logged | 1–2* |
| Mar 25 | 2 | 21:53 | 22:05 | 12m logged | 0.5–1.5* |

> \* "Logged span" is short because most prep/debugging time happens before the first commit. Estimates are padded accordingly.

**Speediance total: ~19–33 hours**
**Best single estimate: ~25 hours**

### Smart Gym Coach

| Date | Commits | Earliest | Latest | Est. Hours |
|---|---|---|---|---|
| Mar 21 | 5 | 15:00 | 23:21 | 2.5–4 |
| Mar 23 | 2 | 00:43 | 00:48 | 1–2 |

**Smart Gym Coach total: ~3.5–6 hours**
**Best single estimate: ~4.5 hours**

### Grand Total

| | Conservative | Best Estimate | Liberal |
|---|---|---|---|
| Speediance Workout Manager | 19 hrs | 25 hrs | 33 hrs |
| Smart Gym Coach | 3.5 hrs | 4.5 hrs | 6 hrs |
| **Total** | **22.5 hrs** | **~30 hrs** | **39 hrs** |

---

## Smart Gym Coach Full Log

**Repo:** https://github.com/ANPC86/claude-smart-gym-coach
**Local:** `[local development path omitted]`
**All commits by ANPC86**

| Timestamp | Commit Message |
|---|---|
| 2026-03-21 15:00 -0600 | Initial commit: Claude Smart Gym Coach project setup |
| 2026-03-21 15:02 -0600 | Initial commit |
| 2026-03-21 15:03 -0600 | Merge remote-tracking branch 'origin/main' - resolve README conflict |
| 2026-03-21 15:59 -0600 | Update README to clarify exercise library cache |
| 2026-03-21 23:21 -0600 | Remove specific exercise count, keep language generic |
| 2026-03-23 00:43 -0600 | Migrate exercise tracking from JSON file to Notion Exercise Library |
| 2026-03-23 00:48 -0600 | Add .gitignore to exclude personal staging folder |

**Reflog evidence:**
```
2026-03-21 15:00  Initial commit (project created)
2026-03-21 15:02  GitHub initial commit
2026-03-21 15:03  Merge conflict resolved with origin/main
2026-03-21 15:59  README update
2026-03-21 23:21  Remove exercise count text
2026-03-23 00:43  Migrate to Notion (pull --rebase against origin/main)
2026-03-23 00:45  Rebase completed
2026-03-23 00:48  .gitignore added
```

---

## Notes on Methodology

### What this data IS
- **Commit timestamps** are exact and reliable — git stores these as Unix timestamps
- **Reflog** reveals branch operations between commits, giving session window bounds
- **Stash entries** prove in-progress work was interrupted and saved (GitHub Desktop behavior)
- **Duplicate commits** in the Speediance log reflect the feature-branch → qa/combined merge workflow, not extra work

### What this data IS NOT
- Active keyboard/editing time (WakaTime would provide this)
- Time spent in Claude.ai conversations designing features
- Time spent reading documentation, Speediance API, testing on QA NAS
- Time spent deploying to the Docker NAS

### Why 2025 is upstream-only
You forked the project in early 2026. The 2025 commits are from hbui3 (the original developer, Hendrik Buisker) and two external contributors. They appear in your git history because git preserves full ancestry. Your first commit to the fork was 2026-02-15 18:02 MST.


---

*Generated from: `git log --all`, `git reflog`, `git shortlog`, `git stash list`*
*Repos: UnofficialSpeedianceWorkoutManager · claude-smart-gym-coach*
