# Jynx — Arcane Theme for VS Code

A dark theme inspired by **Jinx from Arcane**. Electric-blue hair, hot-pink Powder tattoos, and shimmer purple set against the deep, gritty dark of Zaun.

## Palette

**Software / UI** — Powder pink against the dark teals of Zaun:

| Role | Hex |
|------|-----|
| Pink accent (cursor, badges, active borders) | `#FF0099` |
| Chrome (activity bar, sidebar, tabs, status bar) | `#08191D` |
| Editor background | `#0C2730` |
| Line highlight / elevated | `#11313C` |
| Borders / selection | `#1C4452` |

**Code text** — pink, white, green, blue:

| Role | Hex |
|------|-----|
| Default text / variables | `#E6E6E6` (white) |
| Keywords / tags / storage | `#FF0099` (pink) |
| Strings / numbers / constants | `#00E000` (green) |
| Functions / types | `#5B6CFF` (blue) |
| Comments | `#52707A` (muted teal) |
| Errors | `#FF3D6E` |

> The blue is lightened slightly from a pure blue swatch so it stays legible on the dark teal background.

## Install & try it locally

No build step needed — it's a static theme.

1. Copy this folder into your VS Code extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions\jynx-theme`
2. Restart VS Code.
3. Open the Command Palette (`Ctrl+Shift+P`) → **Preferences: Color Theme** → select **Jynx (Arcane)**.

### Or preview without installing

Open this folder in VS Code and press `F5` to launch an Extension Development Host, then pick the theme there.

### Package as a `.vsix` (optional)

```bash
npm install -g @vscode/vsce
vsce package
```

This produces `jynx-theme-1.0.0.vsix`, which you can install via
**Extensions → ⋯ → Install from VSIX…**

## License

MIT
