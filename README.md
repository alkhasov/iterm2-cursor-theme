# Cursor Theme for iTerm2

A color theme for **iTerm2** terminal based on the **Cursor** editor color palette (Light & Dark).

![Light & Dark](https://img.shields.io/badge/Theme-Light%20%26%20Dark-blue)

## Files

| File | Description |
|------|-------------|
| `Cursor Light Theme.itermcolors` | Light theme (colors only) |
| `Cursor Dark Theme.itermcolors` | Dark theme (colors only) |
| `Cursor-Theme.json` | Profile with automatic Light/Dark switching |

## Installation

### Option 1: Profile with Auto-Switching (Recommended)

Use the `.json` file to create a profile that **automatically switches colors** when macOS system appearance changes (Light ↔ Dark).

1. Open **iTerm2** → **Settings** (⌘,)
2. Go to **Profiles**
3. In the bottom left corner click **Other Actions...** → **Import JSON Profiles...**
4. Select the `Cursor-Theme.json` file
5. The **"Cursor Theme"** profile will appear in the list

Now your terminal will automatically change colors along with the system!

### Option 2: Colors Only (Separate)

Use `.itermcolors` files if you want to apply colors to an existing profile.

1. Open **iTerm2** → **Settings** (⌘,)
2. Go to **Profiles** → select a profile → **Colors**
3. In the bottom right click **Color Presets...** → **Import...**
4. Select the desired file:
   - `Cursor Light Theme.itermcolors` — for light theme
   - `Cursor Dark Theme.itermcolors` — for dark theme
5. Open **Color Presets...** again and select the imported theme

## Color Palette

### Light Theme
| Color | Hex | Purpose |
|-------|-----|---------|
| Background | `#FFFFFF` | Background |
| Foreground | `#383A42` | Text |
| Red | `#E45649` | Errors |
| Green | `#50A14F` | Success |
| Yellow | `#C18501` | Warnings |
| Blue | `#4078F2` | Key elements |
| Magenta | `#A626A4` | Keywords |
| Cyan | `#0184BC` | Strings, types |

### Dark Theme
| Color | Hex | Purpose |
|-------|-----|---------|
| Background | `#1E1E1E` | Background |
| Foreground | `#D4D4D4` | Text |
| Red | `#E06C75` | Errors |
| Green | `#98C379` | Success |
| Yellow | `#E5C07B` | Warnings |
| Blue | `#61AFEF` | Key elements |
| Magenta | `#C678DD` | Keywords |
| Cyan | `#56B6C2` | Strings, types |

## Compatibility

- iTerm2 3.4+ (for Light/Dark auto-switching support)
- macOS 10.14+ (Mojave and later)

## License

MIT
