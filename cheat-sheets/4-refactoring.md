**Step One**: On line 11 of main.js, add the following code chunk:

```js
  var menubar = require('menubar')
  var mb = menubar()

  mb.on('ready', function ready () {
    console.log('app is ready')
    // your app code here
  })
```

**Step Two**: Comment out ALL remaining lines (18 - 95) of code on main.js

**Step Three**: Save. Then launch the app:
```sh
npm start
```
**Step Four**: Notice the Electron error pop-up.

**Step Five**: Return to package.json, and add a comma to the end of line 20.
```js
"electron": "^1.6.8",
```
**Step Six**: On line 21, paste the following:
```js
"menubar": "^5.2.3"
```
**Step Seven**: Install the new dependency and restart the app.
```sh
npm install
```
```sh
npm start
```

#### Jump to [Next Exercise](5-packaging.md)
