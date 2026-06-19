# Jynx — Cyberpunk Themes for VS Code

A set of dark themes inspired by **Jinx from Arcane** and neon cyberpunk: electric pink accents, deep gritty backgrounds, and high-contrast neon syntax highlighting.

## Variants

The extension ships three color themes — pick one from the theme picker:

| Theme | Vibe |
|-------|------|
| **Jynx — Neon Punk** | The flagship: electric pink over deep purple-black with magenta/cyan/lime/yellow neon syntax |
| **Jynx — Cyberpunk Neon** | A brighter, higher-voltage cyberpunk take |
| **Jynx — Cyberpunk Neon (Blue/Gold)** | Cyberpunk palette with blue + gold accents |

## Palette (Neon Punk)

**UI** — electric pink over deep purple-black:

| Role | Hex |
|------|-----|
| Pink accent (cursor, badges, active borders) | `#FF0099` |
| Chrome (activity bar, sidebar, tabs, status bar) | `#08060F` |
| Editor background | `#0D0B1A` |
| Line highlight / elevated | `#161228` |
| Borders / selection | `#2A2547` |

**Code text** — pink, white, green, cyan:

| Role | Hex |
|------|-----|
| Default text / variables | `#ECECF2` (white) |
| Keywords / tags / control | `#FF0099` (pink) |
| Strings | `#00E000` (neon green) |
| Functions | `#00ffff` (electric cyan) |
| Classes / types | `#c084fc` (lavender) |
| Numbers | `#ff9500` (orange) |
| Comments | `#a78bfa` (purple italic) |
| Markdown `##` / `**` / `\|` / `---` | `#fde047` (yellow) |

## Install & try it locally

No build step needed — these are static themes.

1. Copy this folder into your VS Code extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions\jynx-theme`
   - macOS / Linux: `~/.vscode/extensions/jynx-theme`
2. Restart VS Code.
3. Open the Command Palette (`Ctrl+Shift+P`) → **Preferences: Color Theme** → pick a **Jynx** variant.

### Or preview without installing

Open this folder in VS Code and press `F5` to launch an Extension Development Host, then pick a theme there.

### Package as a `.vsix` (optional)

```bash
npm install -g @vscode/vsce
vsce package
```

This produces `jynx-theme-1.0.0.vsix`, which you can install via
**Extensions → ⋯ → Install from VSIX…**

## License

MIT
