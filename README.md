# Minimal VS Code Extension Pack

VS Code allows you to create Extension Packs to conviniently install multiple extensions at once. However, the instructions I could find involved installing a lot of packages (`nodejs`, `npm`, `yo` and `vsce`) to accomplish this. That seemed a bit excessive, especially if the extension pack was for personal use.

This method lets you create a VS Code Extension Pack in VSIX format without installing anything! Turns out a VSIX package is simply zipfile with a directory named `extension` in its root directory 😉

## Instructions

- Fork this repo and edit `package.json` to include your desired extensions. 
- Download the edited repo as a zip file and change the extension to `.vsix`.
- Install using `Extensions: Install from VSIX`.
