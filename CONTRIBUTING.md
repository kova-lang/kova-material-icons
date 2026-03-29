# Contributing to Kova Material Icons

Thanks for your interest in contributing! This extension adds `.kova` file icon support on top of the Material Icon Theme.

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/kova-lang/kova-material-icons.git
cd kova-material-icons
```

### 2. Install dependencies

```bash
npm install
```

### 3. Build

```bash
npm run build
```

### 4. Test in VS Code

- Open the project folder in VS Code
- Press `F5` to launch the **Extension Development Host**
- In the new VS Code window, open any folder containing `.kova` files
- Go to **File → Preferences → File Icon Theme** and select **Material Icon Theme**
- You should see the Kova icon appear next to `.kova` files

## Adding or Updating Icons

- All icons live in the `icons/` folder as `.svg` files
- File icon mappings are registered in `src/core/icons/fileIcons.ts`
- Each entry follows this shape:

```ts
{ name: 'kova', fileExtensions: ['kova'] }
```

- After making changes, rebuild with `npm run build` and press `F5` to test

## Submitting Changes

1. Fork the repo
2. Create a branch: `git checkout -b my-change`
3. Make your changes and rebuild
4. Open a Pull Request against `main`

## Questions?

Open an issue on [GitHub](https://github.com/kova-lang/kova-material-icons/issues).