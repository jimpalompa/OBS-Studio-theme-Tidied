# OBS Studio theme: Tidied

Tidied is a style for OBS Studio's built-in Yami theme. It keeps Yami's look and tidies up a few layout details. I needed to tidy up and hide certain unused things when using a small resolution (1600x900) on my TV. The style is for my own personal preferences.

Tested and working on OBS Studio 32.2.2.

## What it changes

- **Preview:** the zoom and scaling bar and the preview scrollbars are hidden.
- **Studio Mode:** the transitions panel between Preview and Program is hidden, and the Preview/Program titles are smaller.
- **Scenes dock:** the scene list is inset like the Controls dock, and in grid mode the scene buttons are sized and spaced like the Controls buttons.
- **Controls dock:** the gap between the Stream and Broadcast buttons matches the rest of the dock, and the virtual camera and settings buttons are hidden.

## Installation

1. Copy `yami_tidied.ovt` to the OBS themes folder:
   - macOS: `~/Library/Application Support/obs-studio/themes`
   - Windows: `%APPDATA%\obs-studio\themes`
   - Linux: `~/.config/obs-studio/themes`
2. Restart OBS.
3. In **Settings > Appearance**, set **Theme** to **Yami** and **Style** to **Tidied**.
