# Armada Color Theme

Dark and Light themes based on JetBrains Fleet aesthetics, ported from [Armada Core Themes](https://github.com/DavidSeptimus/armada-theme-intellij-plugin) for IntelliJ.

## Themes

| Theme | Description |
|-------|-------------|
| **Armada Dark** | Fleet-inspired dark UI and syntax |
| **Armada Light** | Fleet-inspired light UI and syntax (close to the IntelliJ original) |
| **Armada Light v2** | Reading-oriented light variant: warm paper surfaces (`#F1F1EE`), Oklab-aligned syntax accents, receding warm comments, stronger secondary UI contrast |

### Armada Light v2 notes

- **Surfaces** — Shared warm paper shell for editor, sidebar, panel, status bar, and terminal (less glare than pure white).
- **Syntax** — Main accent tokens (keyword, type, function, string, constants, decorator) aligned on a similar perceived lightness band. Module keywords (`export`, `import`, `from`) use a wine accent (`#863854`); `const`, `return`, and `if` stay on the storage teal. Comments sit one step lighter (`#626058`) so code stays in front while long notes remain readable.
- **Accessibility** — Primary syntax and main UI text target WCAG AA on the paper background; secondary UI greys (line numbers, inlay hints, placeholders) were raised for clearer contrast. Structural borders stay subtle by design.

Pick a theme via **Preferences: Color Theme**.

## Install (local)

1. Open this folder in VS Code / Cursor
2. Press `F5` to launch an Extension Development Host
3. `Preferences: Color Theme` → choose **Armada Dark**, **Armada Light**, or **Armada Light v2**

Or package and install:

```bash
npx @vscode/vsce package
code --install-extension armada-color-theme-0.12.0.vsix
```

## Credits

Color scheme adapted from [Armada Core Themes](https://github.com/DavidSeptimus/armada-theme-intellij-plugin) by David Septimus (MIT).
