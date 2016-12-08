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

## Development Web Server
We run a local webserver on port 3000. The webserver can be started with `npm run server`.

In order to share the work-in-progress, [Localtunnel](https://localtunnel.github.io/www/) is used.

1. run `npm install localtunnel -g` 
2. start webserver (`npm run server`) and keep it running
3. run `lt --port 3000`. This return u an url you can share to access your current work-in-progress

 

