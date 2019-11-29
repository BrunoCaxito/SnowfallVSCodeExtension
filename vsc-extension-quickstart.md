# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file in which you declare your language support and define the location of the grammar file that has been copied into your extension.
* `syntaxes/vn.tmLanguage.json` - this is the Text mate grammar file that is used for tokenization.
* `language-configuration.json` - this is the language configuration, defining the tokens that are used for comments and brackets.

## Get up and running straight away

* Make sure the language configuration settings in `language-configuration.json` are accurate.
* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that syntax highlighting works and that the language configuration settings are working.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Add more language features

* To add features such as intellisense, hovers and validators check out the VS Code extenders documentation at https://code.visualstudio.com/docs

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

---

## What's in the folder

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/Snowfall Script Theme-color-theme.json` - the color theme definition file.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Inspect TM Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.
