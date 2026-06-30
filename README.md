# Smart Gym Workout Manager

Custom workout builder and history tools for SmartGym / Speediance-style training workflows.

---

## Credits

Originally based on [Unofficial Speediance Workout Manager](https://github.com/hbui3/UnofficialSpeedianceWorkoutManager) by [hbui3](https://github.com/hbui3).

This project has since been substantially modified for personal SmartGym workout management, workout building, history analysis, exports, and metric/unit handling.

---

This project may continue to function as long as the API remains accessible, but is subject to the same limitations described above. Use at your own risk.

---

## Support

If this project helps you, sponsorship is appreciated but never required.

<a href="https://www.buymeacoffee.com/ANPCAI" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" width="180">
</a>

---

## Changes & Features in This Fork

### Latest Release
- **History detail totals fixed** - workout detail headers now use the same duration, calories, and volume shown in the history listing
- **Preset saving fixed** - preset ID `0` is preserved when saving and editing workouts, preventing Warm Up-style presets from being saved as Customize
- **Preset regression coverage** - unit coverage now verifies preset IDs `-1`, `0`, `1`, `3`, and `5` pass through to the Speediance payload correctly

### Workout Builder Enhancements
- **Live stats bar** — shows total exercises, estimated volume, total time, and rest time as you build
- **Move to top / bottom buttons** — quickly reorder exercises without repeated dragging
- **Redesigned header** — two-row layout with stats aligned to the right for a cleaner look
- **Est. Burn chip** — displays estimated calorie burn alongside other stats
- **Target Muscles radar chart** — visual breakdown of which muscle groups your workout covers
- **Vita exercise support** — correctly handles Vita exercises (level 1–10) in the builder and when saving
- **Cardio/timed exercises** — time input and dynamic preset dropdown work correctly for row, ski, and kcal modes
- **Condensed workout cards** — all key stats shown in a single line per exercise

### Workout History
- **Full history page** — view all past workouts with date, duration, calories, and exercise details
- **Export options** — download your workout history as a file
- **Accurate timestamps** — dates display in your local timezone rather than a fixed region

### My Workouts (Home Page)
- **Workout count** — heading shows how many custom workouts you have at a glance
- **Improved layout** — reorganized and sorted for easier navigation

### Calendar
- **Day offset correction** — calendar highlights the correct day regardless of your timezone

### API Debug Console
- **Debug panel** — floating button reveals the last raw API response, useful for troubleshooting connection or data issues

### Weight Unit Handling (Imperial / Metric)
- **Accurate LBS storage** — weights entered in Imperial are stored and retrieved correctly without incorrect unit conversion being applied

---

## Running with Docker

A `docker-compose.yml` template is included for running the app in a container.

**Before starting**, edit the `volumes` path to point to the folder where you unzipped or cloned this repository:

```yaml
volumes:
  - /path/to/your/app:/app
```

- **Windows example:** `/c/Users/yourname/Downloads/SmartGymWorkoutManager`
- **Linux / Synology NAS example:** `/volume1/docker/smart-gym-app`

Then run:

```bash
docker compose up -d
```

The app will be available at `http://localhost:5001`.
