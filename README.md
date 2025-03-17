# mpv-copyStuff

This script copies to clipboard the:
- Filename (With Extension) or URL Link
- Full Filename Path
- Current Video Time (HH:MM:SS.MS)
- Current Displayed Subtitle Text
- Video Metadata

## Installation

Put the script `copyStuff.lua` in your scripts folder, usually in:
- Windows: `"C:\Users\Username\AppData\Roaming\mpv\scripts"`.
- Linux and MacOS: `"~/.config/mpv/scripts/"`.

To work, the script needs:
- Windows: `Powershell`.
- Linux/X11: `xclip`.
- Linux/Wayland : `xclip` or `wl-clipboard`.
- MacOS: `pbcopy` (not tested).

## Hotkeys

<div align="center">

| What is Copied                       | Hotkey     |
| ------------------------------------ | ---------- |
| **Filename or URL Link**             | **CTRL+f** |
| **Full Filename Path**               | **CTRL+p** |
| **Current Video Time (HH:MM:SS.MS)** | **CTRL+t** |
| **Current Displayed Subtitle Text**  | **CTRL+s** |
| **Video Duration**                   | **CTRL+d** |
| **Video Metadata**                   | **CTRL+m** |

</div>

# Screenshots

![ss1](https://raw.githubusercontent.com/raphaeltannous/screenshots/main/mpv-copyStuff/example_01.png)
![ss2](https://raw.githubusercontent.com/raphaeltannous/screenshots/main/mpv-copyStuff/example_02.png)
![ss4](https://raw.githubusercontent.com/raphaeltannous/screenshots/main/mpv-copyStuff/example_04.png)
![ss5](https://raw.githubusercontent.com/raphaeltannous/screenshots/main/mpv-copyStuff/example_05.png)
