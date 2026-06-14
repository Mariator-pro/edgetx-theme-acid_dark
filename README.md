# Acid Dark — EdgeTX Theme

A dark EdgeTX theme with an acid lime accent (`0x7CD230`). Built for color radios.

![Main view](src/THEMES/Acid_Dark/screenshot1.png)
![Manage Models](src/THEMES/Acid_Dark/screenshot2.png)
![Theme view](src/THEMES/Acid_Dark/screenshot3.png)

## Palette

Each variable maps to specific UI elements in EdgeTX (per the official
[theme structure reference](https://github.com/EdgeTX/themes/blob/main/structure.md)):

| Role | Color | Swatch | Used for |
|------|-------|--------|----------|
| PRIMARY1 | `0xF0F0F0` | ![F0F0F0](docs/swatches/F0F0F0.png) | Label text and button text (not focused). |
| PRIMARY2 | `0x121412` | ![121412](docs/swatches/121412.png) | ETX logo icon; top-bar icons, text and tab names; bottom-bar text; editable-field background, edited-value text and focused button text; popup field background; trim and slider knobs. |
| PRIMARY3 | `0x969696` | ![969696](docs/swatches/969696.png) | Scroll marker and the inactive part of top-bar icons. |
| SECONDARY1 | `0xF0F0F0` | ![F0F0F0](docs/swatches/F0F0F0.png) | Top-bar and bottom-bar background; trim/slider paths and shadows; slider-knob shadow. |
| SECONDARY2 | `0x0C0E0C` | ![0C0E0C](docs/swatches/0C0E0C.png) | Label background and button background. |
| SECONDARY3 | `0x545854` | ![545854](docs/swatches/545854.png) | Main screen background and popup background. |
| FOCUS | `0x7CD230` | ![7CD230](docs/swatches/7CD230.png) | ETX logo background; selected top-bar icon background; focused label and editable-field backgrounds; trim and slider knobs. |
| EDIT | `0x7CD230` | ![7CD230](docs/swatches/7CD230.png) | Editable-field background while a value is being edited. |
| ACTIVE | `0x37474F` | ![37474F](docs/swatches/37474F.png) | Active button background and editable-field background for an active variable (e.g. switches on, checked boxes). |
| WARNING | `0xFFB400` | ![FFB400](docs/swatches/FFB400.png) | Warning label text. |
| DISABLED | `0x5A5A5A` | ![5A5A5A](docs/swatches/5A5A5A.png) | Disabled UI elements throughout the interface. |

## Install

1. Copy the `src/THEMES/Acid_Dark` folder to the `/THEMES` directory on your
   radio's SD card.
2. On the radio, go to **Radio Setup → Themes** and select **Acid Dark**.

## Backgrounds

The `background_<WxH>.png` files (320x240, 320x480, 480x272, 480x320, 800x480)
are solid fills in the dark background color `0x121412` (RGB 18, 20, 18),
matching `PRIMARY2`. Replace them with your own dark artwork if you want
something behind the menus.
