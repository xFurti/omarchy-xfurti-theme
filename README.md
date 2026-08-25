# xFurti

Dark-tech Omarchy theme for [Leonardo Bassanello](https://github.com/xFurti) — **developer · AI · problem solver**.

Navy void, electric-blue glow, and a warm bronze accent taken from the xFurti banner and avatar. Built for daily use on Hyprland, and installable by anyone on Omarchy.

![xFurti theme preview](preview.png)

## Palette

Colors were sampled from the brand banner and profile art, then tuned for contrast in terminals, editors, and the Omarchy shell.

| Role | Hex | Swatch |
|------|-----|--------|
| Background | `#040a20` | ![](https://placehold.co/48x16/040a20/040a20.png) |
| Darker background | `#010415` | ![](https://placehold.co/48x16/010415/010415.png) |
| Lighter background | `#0e1a32` | ![](https://placehold.co/48x16/0e1a32/0e1a32.png) |
| Foreground | `#d6e4f5` | ![](https://placehold.co/48x16/d6e4f5/d6e4f5.png) |
| Muted | `#3d4e63` | ![](https://placehold.co/48x16/3d4e63/3d4e63.png) |
| **Accent** | `#00a3ff` | ![](https://placehold.co/48x16/00a3ff/00a3ff.png) |
| Cyan (HUD) | `#15d5f9` | ![](https://placehold.co/48x16/15d5f9/15d5f9.png) |
| Yellow / bronze | `#ed964f` | ![](https://placehold.co/48x16/ed964f/ed964f.png) |
| Orange | `#c87438` | ![](https://placehold.co/48x16/c87438/c87438.png) |
| Brown | `#5b3013` | ![](https://placehold.co/48x16/5b3013/5b3013.png) |
| Green | `#2ec9a0` | ![](https://placehold.co/48x16/2ec9a0/2ec9a0.png) |
| Red | `#f25a7a` | ![](https://placehold.co/48x16/f25a7a/f25a7a.png) |
| Magenta | `#8b7eff` | ![](https://placehold.co/48x16/8b7eff/8b7eff.png) |

Active Hyprland borders use an electric-blue → HUD-cyan gradient:

```toml
hyprland_active_border = "rgba(00a3ffee) rgba(15d5f9ee) 45deg"
```

`colors.toml` is the single source of truth. Omarchy generates configs for Foot, Alacritty, Ghostty, Kitty, btop, Chromium, Hyprland, Neovim, Helix, VS Code, Obsidian, RGB keyboards, and the entire Omarchy shell (bar, menu, notifications, OSD, lock screen).

## Install

```bash
omarchy-theme-install https://github.com/xFurti/omarchy-xfurti-theme.git
```

Or from the Omarchy menu: **Install → Style → Theme**, then paste the same URL.

After install the theme appears as **xfurti**. Apply it anytime with:

```bash
omarchy theme set xfurti
```

Cycle wallpapers with `Super + Ctrl + Space` (or `omarchy theme bg next`).

Custom unlock art is included. Pick it under **Style → Unlock**.

## Wallpapers

Cycle with `Super + Ctrl + Space`. All ten are 4K, navy + electric blue, and built around tech / AI motifs.

| Neural void | Circuit halo |
| --- | --- |
| ![Neural void](backgrounds/01-neural-void.png) | ![Circuit halo](backgrounds/02-circuit-halo.png) |
| **Constellation** | **Aperture** |
| ![Constellation](backgrounds/03-constellation.png) | ![Aperture](backgrounds/04-aperture.png) |
| **Architecture** | **Attention** |
| ![Architecture](backgrounds/05-architecture.png) | ![Attention](backgrounds/06-attention.png) |
| **Weights** | **Latent** |
| ![Weights](backgrounds/07-weights.png) | ![Latent](backgrounds/08-latent.png) |
| **Bitstream** | **Chip** |
| ![Bitstream](backgrounds/09-bitstream.png) | ![Chip](backgrounds/10-chip.png) |

## Screenshots

Live desktop captures after install:

| Desktop | Terminal | Neovim |
| --- | --- | --- |
| _Add `docs/desktop.png`_ | _Add `docs/terminal.png`_ | _Add `docs/neovim.png`_ |

| btop | Lock screen |
| --- | --- |
| _Add `docs/btop.png`_ | ![Unlock preview](preview-unlock.png) |

## Structure

```
omarchy-xfurti-theme/
├── colors.toml           # Required palette (semantic + ANSI)
├── icons.theme           # Yaru-blue
├── keyboard.rgb          # Framework / ROG RGB
├── shell.lock.toml       # Lock screen chrome
├── backgrounds/          # Ten 4K tech/AI wallpapers
├── unlock.png            # Plymouth unlock mark (transparent)
├── preview.png           # Theme switcher card
├── preview-unlock.png    # Unlock preview
├── README.md
└── LICENSE
```

Follows the official Omarchy layout: [Making your own theme](https://omarchy.org/manual/making-your-own-theme/).

## Credits

- Brand, banner, and avatar: [Leonardo Bassanello (xFurti)](https://github.com/xFurti)
- Theming model: [Omarchy](https://omarchy.org/) by [DHH](https://dhh.dk/) / [37signals](https://37signals.com/)
- File manager icons: Yaru-blue

## License

[MIT](LICENSE)
