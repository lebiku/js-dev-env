# js-dev-env
Javascript Development Environment - Starter Kit
In order to edit/master this file check [Markdown](https://guides.github.com/features/mastering-markdown/)

# Toolchain Decisions
The toolchain decisions are critical. Consider it as a checklist or receipt and make sure that steps are not forgotten (critical) 

## Editors and Configurations
* Visual Studio Code 
* [Editorconfig](http://editorconfig.org/) for formatting (Download / Install the plugin in Visual Studio Code)

## Package Manger (npm)
Open Visual Studio Code in root directory and open inline terminal (Ctrl ¨).

1. run `npm install` (all packages in package.json are installed)
2. For module security Checking run node security platform
  1. run `npm install -g nsp`
  2. run `nsp check` in the command line

