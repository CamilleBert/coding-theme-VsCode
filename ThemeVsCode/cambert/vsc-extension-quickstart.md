
## Do you want to create your own custom theme VS Code ?

#### 1. What you need :
- _Node.js_ : https://nodejs.org/en/download/
- _Git_ : https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

#### 2. Open a terminal and type : 
`npm install -g yo generator-code`

`yo code`

<img width="274" alt="image" src="https://user-images.githubusercontent.com/60038113/190916202-f173cdfc-ad23-4280-b3e8-f13778ea1b8d.png">

#### 3. Select the informations : 
      3.1 Select New Color Theme 
      3.2 Select No, start fresh
      3.3 Type the name of your extension (ex : cambert)
      3.4 Type an id/a short description/a public name/theme (Dark, Light or High contrast)
      3.5 Open the folder in Visual Studio Code

#### 4. Press `fn + f5` on Mac or `f5` on Windows _(or Execute > Execute Debugger)_
If you modify and save the file json (in the folder `themes`), the result will appear on the second window.
## What's in the folder themes ?

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/cambert-color-theme.json` - the color theme definition file.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.
