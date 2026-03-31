# Kova Material Icons

A VS Code icon theme that extends [Material Icon Theme](https://github.com/PKief/vscode-material-icon-theme) with first-class support for the [Kova language](https://github.com/kova-lang/kova).

If you're writing `.kova` files, your editor should feel like home. This extension makes sure of that.

---

## What it does

- Adds a dedicated icon for `.kova` files in the VS Code file explorer
- Keeps all the icons you already love from Material Icon Theme - nothing breaks, we just add Kova on top

---

## Setup

### Option 1 - Install from VS Code Marketplace

1. Open VS Code
2. Go to the **Extensions** panel (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for **Kova Material Icons**
4. Click **Install**

### Option 2 - Install from GitHub Releases

1. Go to the [Releases page](https://github.com/kova-lang/kova-material-icons/releases)
2. Download the latest `kova-material-icons-x.x.x.vsix` file
3. Install it via terminal:

```bash
code --install-extension kova-material-icons-x.x.x.vsix
```

Or in VS Code: **Extensions** → `...` menu → **Install from VSIX** → select the downloaded file

---

## How to use it

### Switching to the Kova icon theme

After installing, you need to activate the theme:

1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Type **File Icon Theme**
3. Select **Kova Material Icons** from the list

Your file explorer will now show the Kova icon next to any `.kova` file.

You can also set it via VS Code settings:

```json
{
  "workbench.iconTheme": "kova-material-icons"
}
```

### VS Code settings

| Setting | Value | What it does |
|---|---|---|
| `workbench.iconTheme` | `"kova-material-icons"` | Activates the Kova icon theme |

You can add this to your **Workspace settings** (`.vscode/settings.json`) to make the theme automatic for everyone working on a Kova project - no manual switching needed.

```json
// .vscode/settings.json
{
  "workbench.iconTheme": "kova-material-icons"
}
```

### Pairing with the Kova language extension

A dedicated Kova language extension (with syntax highlighting, LSP support, and more) is coming soon. Once available, the two extensions will work together out of the box - install both and your `.kova` files will have full editor support from icons to intellisense.

👉 Watch [kova-lang](https://github.com/kova-lang) on GitHub to get notified when it drops.

---

## Contributing

Want to improve the icons or add support for more Kova file types? See [CONTRIBUTING.md](./CONTRIBUTING.md) - it's a quick read.

---

Built with ❤️ by the [Kova team](https://github.com/kova-lang).
