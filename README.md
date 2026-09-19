## v1.0.3
- **Redesigned the update-available popup** to match the app's theme, with a live download progress bar built in instead of a plain system dialog
- **Added Battle.net game detection**
- **Added a per-game "Exclude from Compress All / Queue" toggle**, with a lock badge shown on excluded games
- **Drives page file trees now persist across restarts** instead of rescanning every time
- **Added a "last scanned" timestamp** to Game Library
- **Added a warning before clearing your saved library** while a scan is still running
- **Added a notification when the startup auto-scan finishes**
- **Added a Copy Path button** to Drives' file details panel
- **Hovering a game's Saved/potential column** in Game Library now shows why that compression algorithm was recommended
- **Added optional background update checks** — runs quietly once a day, even when the app is closed, and shows a Windows notification if an update is found
- **Added a low disk space warning before restoring games**, since restoring grows them back to their original size
- **Added Backup & Restore in Settings** — export your library, settings, and activity history to a single file, and import it back later
- **Added a "space saved over time" chart to Dashboard**, tracking the last 30 days

## v1.0.2
- **Fixed the Steam Wishlist page**, which had broken after Valve changed how wishlist data is served
- **Added live compression/restore speed (MB/s)** alongside the existing time-remaining estimate
- **Added a real download progress bar** (MB downloaded / total) when installing app updates
- **Added the Changelog page** — opens automatically the first time you launch a new version

## v1.0.1
- **Added "Check For Updates" in settings tab**

## v1.0.0
- **Initial release**
- Full page set: Dashboard, Game Library, Updates, Queue, Drives, Decompress, Activity, Settings, and How to Use
- Automatic compression algorithm selection per game — no manual picking required
- Game detection across Steam, Epic, GOG, Ubisoft Connect, and EA app, plus manual add
- Anti-cheat detection and warnings, with confirmation prompts before batch-compressing flagged games
- Persistent library that survives restarts, with automatic removal of games no longer installed
- System tray support, minimize-to-tray, and launch-on-startup via a scheduled task
- Steam Store browser with live pricing, a self-refreshing most-played chart, and multi-currency support
- Steam library value Calculator, including owned-but-not-installed games
- One-click launch buttons for Steam and Epic games
- A full dark, glowing "gaming" theme across every page
- A real Windows installer with Start Menu/Desktop shortcuts and clean uninstall
