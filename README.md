# OLED-Spotifast-theme

A true-black theme for [Spotifast](https://spotifast.rocks/), with charcoal surfaces, cool white text and mint accents. Inspired by the bundled Nord and Tokyo Night palettes.

## Install

1. Download [OLED-Spotifast-theme.json](OLED-Spotifast-theme.json) using **Raw → Save as**.
2. In **Settings → Appearance**, click **Open themes folder** and copy the JSON file there. Create the folder if installing manually:

   | OS | Themes folder |
   | --- | --- |
   | Linux | `~/.config/spotifast/themes/` (or `$XDG_CONFIG_HOME/spotifast/themes/`) |
   | macOS | `~/Library/Application Support/me.paolino.spotifast/themes/` |
   | Windows | `%APPDATA%\paolino\spotifast\config\themes\` |

   Linux Flatpak: `~/.var/app/rocks.spotifast.Spotifast/config/spotifast/themes/`. Windows portable: `spotifast-data\config\themes\` beside `spotifast.exe`.

3. Restart Spotifast, or run `spotifast reload-themes` if its command is on your PATH. Select **OLED-Spotifast-theme** under **Settings → Appearance → Theme**.

Turn off **Colour from album art** to keep the black backgrounds. Requires Spotifast 0.11.0 or newer.

The subtle glass-like look comes from colors and outlines; real blur and desktop transparency are outside the palette format. This themes the main window. The `skins/` folder is for separate Winamp mini-player skins.

[Official theme guide](https://spotifast.rocks/settings-and-files/#custom-themes)
