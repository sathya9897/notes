# Electron Basics

- There are 2 types of process in electron app: Main and Renderer.
- Main is nodejs process which runs the application.
- while Renderer processes are instances of chromium which are created by Main process.
- It can be thought of Main process as backend and Renderer process as frontend.
- `electron-rebuild` could be used to build native modules from npm for electron.
- To debug run app with `electron --inspect=AnyPort .` and open a chrome browser with `chrome://inspect` url and add debug route to configuration then the app will be shown under Remote Targets.
- There are 3 types of native modules: Main, Renderer and Shared Module APIs.
- `app.getPath(directoryName)` will provide path to the given directory.
- `userData` directory is were we will store app data like db, files, etc.

## BrowserWindow Module

- `new BrowserWindow(config)` can be used to create a broswer window instance with given config.
- `loadFile` should be used to load local files.
- `loadURL` should be used to load remote URLs or files.
- CSS can be used to make regions draggable or not, selectable, etc.
- `electron-window-state` module can be used to save and use window size and position.
-
