# Minimal VS Code Extension Pack

VS Code allows you to create Extension Packs to conviniently install multiple extensions at once. However, the instructions I could find involved installing a lot of packages (`nodejs`, `npm`, `yo` and `vsce`) to accomplish this. That seemed a bit excessive, especially if the extension pack was for personal use.

This method lets you create a VS Code Extension Pack in VSIX format without installing anything!

## Instructions

- Edit `package.json` to include your desired extensions. 
- Create a zip file with extension `.vsix` such that the directory named `extension` is in its root. For example, from within `vscode-extension-pack-minimal`, you could use 
```bash
zip -r ExtensionPackMinimal.vsix ./extension  
```
- Install using `Extensions: Install from VSIX`.
