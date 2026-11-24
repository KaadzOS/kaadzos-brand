<div align="center">
  <img src="https://raw.githubusercontent.com/KaadzOS/.github/main/assets/kaadzoslogo.png" alt="KaadzOS" width="100%">
</div>

## KaadzOS brand kit

The public visual identity of KaadzOS: a true-black AMOLED canvas, white type, a white accent, and neutral near-black surfaces. This repository is a published snapshot for wallpapers, badges and downstream references.

| Asset | File |
| --- | --- |
| Masthead | [`assets/kaadzoslogo.png`](assets/kaadzoslogo.png) |
| AMOLED palette | [`palette`](palette) |
| Wallpaper (SVG) | [`wallpapers/kaadzos-wallpaper.svg`](wallpapers/kaadzos-wallpaper.svg) |
| Wallpaper (PNG) | [`wallpapers/kaadzos-wallpaper.png`](wallpapers/kaadzos-wallpaper.png) |

### Palette

| Role | Hex |
| --- | --- |
| Background | `#000000` |
| Raised base | `#050505` |
| Surface | `#0a0a0a` |
| Overlay | `#161616` |
| Hairline | `#292929` |
| Muted text | `#8a8a8a` |
| Secondary text | `#9c9c9c` |
| Primary text | `#ffffff` |
| Accent | `#ffffff` |
| Urgent | `#ff5c5c` |

Red is reserved for errors and urgent state. The muted green and yellow values in [`palette`](palette) are only for semantic terminal status, not general UI colour.

### Typography

- **UI:** Inter Tight
- **Terminal and code:** JetBrains Mono
- **Fallback:** DejaVu Sans

Inter Tight is licensed under the SIL Open Font License and is vendored in the operating system and on the website; it is not duplicated in this repository.

### Use

The KaadzOS name and masthead identify the project. You may use them to refer to KaadzOS; do not use them to imply that a modified distribution is official.

The source of truth for the palette and generated artwork is [`theme/palette`](https://github.com/KaadzOS/KaadzOS/blob/main/theme/palette) and [`theme/generate.sh`](https://github.com/KaadzOS/KaadzOS/blob/main/theme/generate.sh) in the main repository. This repository is a published snapshot for people who need the assets without cloning the full build tree.

## Licence

The published assets and documentation in this repository are MIT-licensed; see [`LICENSE`](LICENSE). Inter Tight remains under the SIL Open Font License, and the KaadzOS name and masthead remain project identifiers as described above.

<sub>Debian is a registered trademark of Software in the Public Interest, Inc. KaadzOS is an independent project.</sub>
