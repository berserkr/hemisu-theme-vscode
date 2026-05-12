# Hemisu Theme for VS Code

A faithful port of the [Hemisu](https://github.com/noahfrederick/vim-hemisu) Vim color scheme by Noah Frederick to Visual Studio Code, featuring both light and dark variants.

## Color Palette

The theme uses the original Hemisu color assignments:

### Dark Theme
- **Background**: Pure black (`#000000`)
- **Foreground**: Almost white (`#EEEEEE`)
- **Accent 1** (constants, imports): Middle light blue (`#9FD3E6`)
- **Accent 2** (strings, keywords): Middle light green (`#B1D631`)
- **Accent 3** (types, tags): Light green (`#BBFFAA`)
- **Accent 4** (headings, labels): Light tan (`#ECE1C8`)
- **Comments**: Middle dark grey (`#777777`, italic)

### Light Theme
- **Background**: Pure white (`#FFFFFF`)
- **Foreground**: Almost black (`#111111`)
- **Accent 1** (constants, imports): Middle dark blue (`#538192`)
- **Accent 2** (strings, keywords): Middle dark green (`#739200`)
- **Accent 3** (types, tags): Middle dark pink (`#FF0055`)
- **Accent 4** (headings, labels): Dark tan (`#503D15`)
- **Comments**: Middle light grey (`#999999`, italic)

## Install

### From VSIX

1. Download the `.vsix` file from Releases
2. In VS Code: `Extensions` > `...` > `Install from VSIX...`

### From Source

```bash
git clone https://github.com/berserkr/hemisu-theme-vscode.git
cd hemisu-theme-vscode
npx @vscode/vsce package
code --install-extension hemisu-theme-*.vsix
```

## Activation

1. Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Select `Preferences: Color Theme`
3. Choose `Hemisu Dark` or `Hemisu Light`

## Credits

Based on [hemisu.vim](https://github.com/noahfrederick/vim-hemisu) by Noah Frederick (Creative Commons Attribution-NonCommercial 3.0 Unported License).
