# NeoVimBanner

[![VS Code](https://img.shields.io/badge/VS%20Code-%5E1.85.0-blue)](https://code.visualstudio.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![Version](https://img.shields.io/badge/version-0.0.1-orange)](./package.json)

A dark VS Code theme inspired by the Neovim banner aesthetic: muted navy background,
soft contrast, and warm One Dark-style accents. The palette is tuned for long coding
sessions with readable syntax highlighting, calm UI tones, and subtle focus states.

![Theme Preview](https://via.placeholder.com/800x500.png?text=NeoVimBanner+Theme+Preview)

> Replace the placeholder above with an actual screenshot of the theme in action.

## Features

- **Dark theme** with a muted navy base (`#1f232b`) for reduced eye strain
- **134 UI color definitions** covering editor, sidebar, terminal, tabs, menus,
  notifications, git decorations, and more
- **24 syntax highlighting rules** for fine-grained token coloring
- **17 semantic token colors** for enhanced language support (types, interfaces,
  enums, macros, regex, etc.)
- **One Dark-inspired palette** with warm, balanced accents
- **Semantic highlighting** enabled out of the box

## Installation

### From VS Code Marketplace

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for `NeoVimBanner`
4. Click **Install**
5. Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and select
   `Preferences: Color Theme` → **NeoVimBanner**

### From VSIX file

1. Build the package:

   ```bash
   npm install
   npm run dist
   ```

2. Install the generated `.vsix` file:

   ```bash
   code --install-extension neovim-banner-0.0.1.vsix
   ```

### From command line

```bash
code --install-extension aleksandersk.neovim-banner
```

## Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Background | ![#1f232b](https://via.placeholder.com/16/1f232b/1f232b.png) | `#1f232b` |
| Foreground | ![#c8ccd4](https://via.placeholder.com/16/c8ccd4/c8ccd4.png) | `#c8ccd4` |
| Blue (functions) | ![#61afef](https://via.placeholder.com/16/61afef/61afef.png) | `#61afef` |
| Green (strings) | ![#98c379](https://via.placeholder.com/16/98c379/98c379.png) | `#98c379` |
| Yellow (types) | ![#e5c07b](https://via.placeholder.com/16/e5c07b/e5c07b.png) | `#e5c07b` |
| Red (variables) | ![#e06c75](https://via.placeholder.com/16/e06c75/e06c75.png) | `#e06c75` |
| Magenta (keywords) | ![#c678dd](https://via.placeholder.com/16/c678dd/c678dd.png) | `#c678dd` |
| Cyan (operators) | ![#56b6c2](https://via.placeholder.com/16/56b6c2/56b6c2.png) | `#56b6c2` |
| Orange (numbers) | ![#d19a66](https://via.placeholder.com/16/d19a66/d19a66.png) | `#d19a66` |
| Comments | ![#5c6370](https://via.placeholder.com/16/5c6370/5c6370.png) | `#5c6370` |
| Accent | ![#4d7ea6](https://via.placeholder.com/16/4d7ea6/4d7ea6.png) | `#4d7ea6` |

## Supported Syntax

The theme provides dedicated highlighting for the following token categories:

- **Comments** — italic, dimmed gray
- **Strings** — green
- **Numbers & Constants** — orange
- **Keywords & Storage** — magenta
- **Operators & Punctuation** — cyan
- **Functions & Methods** — blue
- **Types, Classes & Interfaces** — yellow
- **Variables & Parameters** — red (parameters italic)
- **Properties** — cyan
- **HTML/JSX Tags** — red
- **Attributes** — orange
- **Namespaces** — cyan
- **Markdown** — headings, bold, italic, code, links, lists
- **Diff** — inserted (green), deleted (red), changed (yellow)

## Contributing

Contributions are welcome! To propose changes:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-change`)
3. Make your changes to `themes/neovim-banner-color-theme.json`
4. Test the theme locally by pressing `F5` in VS Code to launch the Extension
   Development Host
5. Commit your changes and open a Pull Request

## License

This project is licensed under the [MIT License](./LICENSE).

## Credits

Developed with the help of Codex by OpenAI.
