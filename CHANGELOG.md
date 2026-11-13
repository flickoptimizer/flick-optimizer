# Changelog

## 1.1.0 - competitive video settings for more games

- **Competitive video settings, written for you**, now for **Fortnite, Counter-Strike 2 and Apex
  Legends** as well as VALORANT. One switch in each game's menu (or *Apply for me* on its settings card)
  writes the competitive preset into the game's own settings file:
  - **Fortnite** - fullscreen, V-Sync off, frame limit = your refresh rate, dynamic resolution off,
    100% 3D resolution, medium view distance, Low shadows / effects / post-processing / foliage / textures.
  - **Counter-Strike 2** - fullscreen, V-Sync off, NVIDIA Reflex on, medium shadows, low shaders /
    textures / particles, ambient occlusion and FSR off. Every Steam account on the PC.
  - **Apex Legends** - exclusive fullscreen, V-Sync off, adaptive resolution off, no anti-aliasing,
    lowest sun shadows, ambient occlusion and volumetric lighting off.
  - Your resolution and refresh rate are kept. Only settings already in your file are changed, only while
    the game is closed, and read-only files stay read-only. Every value is backed up: *Revert* puts back
    exactly what FLICK changed and keeps what you changed in the game since.
  - If the game (or a cloud sync) puts other values back, the switch shows it and *Watch my PC* repairs it.
- **Repair automatically** also runs when FLICK opens, for settings another app turned off after
  start-up (for example Medal turning Game Mode off).

## 1.0.1

- **Watch my PC** puts back settings undone by Windows or another app at sign-in, quietly, and tells you
  once if an app keeps undoing one.
- **PC Scanner**: no more "outdated" network driver when it already is the newest; **Ignore** button on
  every check.
- **8 more games detected**: Escape from Tarkov, Rust, Hunt: Showdown 1896, Battlefield 6 and 2042,
  Delta Force, Halo Infinite, War Thunder - and sturdier detection (Windows' installed-programs list,
  executables moved by game updates).
- **Feedback** button, access codes for the beta, automatic updates, single window opened in front.

## 1.0.0 - first public release

- **Game optimization**: automatic detection of 14 competitive games (Steam, Epic, Riot, Battle.net,
  EA, Ubisoft) plus any game added by hand, each with its own optimization menu and recommended
  in-game settings.
- **80+ tweaks** with switches that show what is applied, pending changes and one *Apply changes* button.
- **PC scanner** with gaming-readiness checks and one-click fixes.
- **Benchmark** for any game (Intel PresentMon), with an FPS goal and a personal plan.
- **Debloat** list of background apps, **Cleaner**, **Gaming apps** installer and an
  **interrupt tuner** (MSI mode and priority).
- Native installer and uninstaller, restore points and per-setting backups.
