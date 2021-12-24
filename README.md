# README
By Pho Hale
A visually distinct version of DarkOnePro theme.

## Purpose
To reduce cognitive load.

# Building a color theme:

## Resources:
https://themes.vscode.one/faq/publishing-theme
https://code.visualstudio.com/api/extension-guides/color-theme#create-a-new-color-theme
https://code.visualstudio.com/api/working-with-extensions/publishing-extension


## Instlal dependencies:
npm install -g yo generator-code vsce

## Build new color theme
yo code
launches interactive walkthrough. 

## Testing:
Push F5 to test the theme in a new editor. File can be modified and saved, and changes will be reflected in real-time in the test editor window.

## Publishing Extension
cd phodarkoneprocustom
vsce package

## Install your extension
* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.



# Relevent Sections:
editorGroup.border
editorGroupHeader.tabsBackground

tab.border
tab.activeBorder
tab.activeBorderTop

## Border around popovers such as run command
widget.shadow

## Git Decorations are the thing to disable that color the file based on the git status


## Main window titlebar, make more distinct.
titleBar.activeBackground

