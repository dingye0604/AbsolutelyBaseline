# AbsolutelyBaseline

**English** | [中文](./README.zh-CN.md)

An Obsidian theme that keeps [Baseline](https://github.com/aaaaalexis/obsidian-baseline)'s layout, components, and motion, and swaps in a warm, Claude-inspired palette and typography.

AbsolutelyBaseline is a thin styling layer rather than a fork. Workspace layouts, callouts, tables, mobile behavior, filter classes, and every animation still come from Baseline, untouched. What changes is color and type.

| Light | Dark |
| :---: | :---: |
| [![AbsolutelyBaseline in light mode](./screenshot-light.jpg)](./Fig1.jpg) | [![AbsolutelyBaseline in dark mode](./screenshot-dark.jpg)](./Fig2.jpg) |

*Click a screenshot to view it full size.*

> Looking for a glass version? [AbsolutelyGlass](https://github.com/dingye0604/AbsolutelyGlass) builds on this theme and adds frosted panels — plus optional native Windows 11 Acrylic.

## What this theme changes

**Palette.** A warm terracotta accent (`#cc7d5e`) over warm neutrals — `#f9f9f7` in light mode, `#2d2d2b` in dark mode. Links, tags, blockquote rules, tables, and semantic colors are retuned to sit on those backgrounds instead of Baseline's defaults.

**Typography.** Serif for note text and headings, system sans for the interface, monospace for code. Line height and heading scale are set for long-form reading.

**Syntax highlighting.** Separate light and dark code palettes, chosen to stay readable on warm backgrounds without the usual cold blue-grey cast.

Everything else is Baseline, unchanged.

## Installation

### From the community theme browser

1. Open **Settings → Appearance → Themes → Manage**
2. Search for **AbsolutelyBaseline**
3. Select **Install and use**

### Manually

1. Download `manifest.json` and `theme.css` from the [latest release](https://github.com/dingye0604/AbsolutelyBaseline/releases/latest)
2. Create a folder named `AbsolutelyBaseline` inside `<your-vault>/.obsidian/themes/`
3. Put both files in that folder
4. Reload Obsidian, then choose **AbsolutelyBaseline** under **Settings → Appearance → Themes**

## Optional: Style Settings

[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) is not required, but Baseline exposes its workspace layouts through it — Baseline, Fusion, Cupertino, macOS, Classic, and Minimal. Install it if you want to switch between those.

## Credits

AbsolutelyBaseline is a derivative work, and most of what you see is other people's work. Credit where it is due.

### Upstream theme

**[Baseline](https://github.com/aaaaalexis/obsidian-baseline)** by [aaaaalexis](https://github.com/aaaaalexis) — MIT licensed.

AbsolutelyBaseline is Baseline with its color and typography systems replaced. All layout, component, and motion code belongs to Baseline. If you like how this theme *behaves*, that is Baseline's doing.

### Bundled fonts

- **Instrument Serif** — Copyright 2022 The Instrument Serif Project Authors (<https://github.com/Instrument/instrument-serif>), designed by Rodrigo Fuenzalida and Jordan Egstad. Licensed under the [SIL Open Font License 1.1](https://openfontlicense.org). Embedded in `theme.css` as a base64 WOFF2.
- **Inter** — by Rasmus Andersson, SIL Open Font License 1.1. Referenced by name only; Inter ships with Obsidian.

### Color schemes credited inside Baseline

Baseline bundles color-scheme presets adapted from other open-source themes. Those presets ship inside `theme.css`, and Baseline credits their authors in its own source:

- **Catppuccin** (Latte, Frappe, Macchiato, Mocha) — Catppuccin
- **Dracula** — Dracula
- **Nord** — Sven Greb ([svengreb](https://github.com/svengreb))
- **Gruvbox** — Pavel Pertsev ([morhetz](https://github.com/morhetz))
- **Solarized** — Ethan Schoonover ([altercation](https://github.com/altercation))
- **Rosé Pine** — Rosé Pine
- **Everforest** — Sainnhe Park ([sainnhe](https://github.com/sainnhe))
- **Flexoki** — Steph Ango ([kepano](https://github.com/kepano))
- **Melange** — Sergio A. Vargas ([savq](https://github.com/savq))
- **Sanctum** — José Daniel Mourão ([jdanielmourao](https://github.com/jdanielmourao))
- **Tiniri** — Vlad Gerasimov ([vladstudio](https://github.com/vladstudio))
- **Admin** — Konstantin Pschera ([k15a](https://github.com/k15a))
- **Border** — [Akifyss](https://github.com/Akifyss)
- **Iridium** — [kyffa](https://github.com/kyffa)
- **Customization extras** — Bradley Wyatt ([bwya77](https://github.com/bwya77))

Baseline's own README additionally credits **Minimal** ([kepano](https://github.com/kepano)), **AnuPpuccin** ([AnubisNekhet](https://github.com/AnubisNekhet)), **Sanctum**, **Tiniri**, **Border**, and **Iridium** as community themes it drew from, **Chill Jinshu Song** by Warren2060 and **Obsidian Baseline Theme Customization** by bwya77 as extras, and **Craft Docs** as workspace inspiration. Please refer to [Baseline's repository](https://github.com/aaaaalexis/obsidian-baseline) for the authoritative list.

### Inspiration

The palette and typography direction are inspired by **Claude**, Anthropic's AI assistant.

## Disclaimer

This is an independent, community-made theme. It is **not affiliated with, sponsored by, or endorsed by Anthropic**. "Claude" is a trademark of Anthropic PBC, referenced here only to describe the visual style this theme draws on.

## License

[MIT](./LICENSE) © the AbsolutelyBaseline authors, incorporating Baseline © 2025 aaaa​alexis.

Bundled and referenced fonts are licensed separately under the SIL Open Font License 1.1 — see [Credits](#credits).
