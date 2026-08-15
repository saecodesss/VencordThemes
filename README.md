<div align="center">

# Discord Themes

Custom Vencord / BetterDiscord themes — dark, translucent, minimal.

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?logo=discord&logoColor=white)](https://discord.gg/3cQMuTD5ge)
[![Made by sae.codes](https://img.shields.io/badge/made%20by-sae.codes-8A2BE2)](https://github.com/saecodess)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](#license)

</div>

---

## Overview

This repository hosts a collection of custom Discord client themes built on the Neutron CSS core. Each theme pairs a curated background with a matched accent palette, tuned for readability, translucency, and low visual noise.

All themes and their assets are maintained here and showcased in the Discord server linked below, where support and updates are also posted.

## Themes

| Theme | Palette | Preview |
|---|---|---|
| **Onyx** | Monochrome dark / white glass | `assets/darkminimal.jpg` |
| **Makima Red** | Deep red / black | `assets/makimaaa.jpg` |
| **Rezee Purple** | Violet / dark purple | `assets/rezee.png` |
| **Ada Wine** | Burgundy / near-black | `assets/adawong.png` |

Each `.theme.css` file is self-contained — download the one you want, no need to clone the full repo.

## Installation

Requires **Vencord** or **BetterDiscord** installed first.

1. **Download** the theme file (`.theme.css`) you want and save it somewhere you'll remember.
2. **Open your themes folder**
   - Open Discord Settings
   - Go to the **Themes** tab
   - Click **Open Themes Folder**
3. **Move the file** into that folder.
4. **Reload Discord** — `Ctrl + R` (Windows/Linux) or `Cmd + R` (macOS).
5. **Enable the theme**
   - Discord Settings → Themes
   - Toggle the switch next to your theme's name

## Customizing

Every theme exposes its background image, accent colors, blur, and opacity as CSS variables at the top of the file (`:root { ... }`). Open the `.theme.css` file in any text editor and adjust:

| Variable | Controls |
|---|---|
| `--backgroundImage` | Background image URL |
| `--themeColor1` / `--themeColor2` | Accent gradient colors |
| `--backgroundOpacity` | How visible the background image is |
| `--backgroundBlur` | Background blur strength |
| `--homeImage` | Server-list Direct Messages icon |

Background images must be direct links (ending in `.jpg`, `.jpeg`, `.png`, or `.gif`) hosted somewhere Discord's client can load from — GitHub raw links (`raw.githubusercontent.com`) are recommended, as Discord CDN attachment links expire.

## Support & Feedback

Join the Discord server for updates, previews of new themes, and support:

**[discord.gg/3cQMuTD5ge](https://discord.gg/3cQMuTD5ge)**

Found a bug or want to suggest a theme? Open an issue or post in the server, and include:

- The **theme name**
- A **clear description** of the problem
- A **screenshot**, if visual

## License

Released under the MIT License — free to use, modify, and share. Attribution appreciated but not required.

---

<div align="center">

Made with care by **sae.codes**

</div>
