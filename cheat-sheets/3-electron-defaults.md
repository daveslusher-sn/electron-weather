**Step One**: On lines 51 and 52 of main.js, add these two lines of code, then save:
```js
  width: 300,
  height: 450,
```
**Step Two**: See the app in progress.
```sh
npm start
```
**Step Three**: While hovering over the app, type CMD + Option + I (Control + Shift + I for Windows) to open Google Dev Tools. 

**Step Four**: Quit the process and return to main.js.

**Step Five**: Set line 56, resizable, to true, and save.
```js
resizable: true,
```
**Step Six**: Relaunch the app to test resizable windows.
```sh
npm start
```
**Step Seven**: Open Dev Tools again (CMD + Option + I OR Control + Shift + I) and find the error in the console tab.

**Step Eight**: Remove line 93 from index.js, which is causing the error in the console dialog, and save.
```js
REMOVE: sendNotification(weather)
```
**Step Nine**: Terminate and relaunch the app.
```sh
npm start
```
**Step Ten**: Open DevTools again to determine if the console error disappears.

#### Jump to [Next Exercise](4-refactoring.md)
