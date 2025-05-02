# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file in which you declare your language support and define the location of the grammar file that has been copied into your extension.
* `syntaxes/life.tmLanguage.json` - this is the Text mate grammar file that is used for tokenization.
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

* To add features such as IntelliSense, hovers and validators check out the VS Code extenders documentation at https://code.visualstudio.com/api/language-extensions/overview

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/api/working-with-extensions/publishing-extension about publishing an extension.

Variable name scopes
Foreground: variable.other.readwrite.js
variable
meta.definition.variable.name
support.variable
entity.name.variable
constant.other.placeholder
Textmate Scopes
variable.other.readwrite.js
meta.definition.variable.js
meta.var-single-variable.expr.js
meta.var.expr.js
source.js

`semantic token type`	variable
`modifiers`	declaration
`foreground`	variable.other.readwrite.js
 * variable
 * meta.definition.variable.name
 * support.variable
 * entity.name.variable
 * constant.other.placeholder
 * { "foreground": "#9CDCFE" }

`textmate scopes`
 * variable.other.readwrite.js
 * meta.definition.variable.js
 * meta.var-single-variable.expr.js
 * meta.var.expr.js
 * source.js

 semantic token type	enumMember
foreground	variable.other.enummember.cpp
variable.other.constant
variable.other.enummember
{ "foreground": "#4FC1FF" }
textmate token	·LM_MANUAL_ROT (14)
textmate scopes	meta.conditional.case.cpp
meta.body.switch.cpp
meta.block.switch.cpp
meta.block.cpp
meta.block.cpp
meta.body.function.definition.cpp
meta.function.definition.cpp
source.cpp