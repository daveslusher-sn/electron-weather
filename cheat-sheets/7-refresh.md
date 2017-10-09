**Step One**: Create a gulpfile.js in your repository:
```js
'use strict';

var gulp = require('gulp');
var electron = require('electron-connect').server.create();

gulp.task('serve', function () {

 // Start browser process
 electron.start();

 // Restart browser process
 gulp.watch('app.js', electron.restart);

 // Reload renderer process
 gulp.watch(['index.js', 'index.html'], electron.reload);
});
```
**Step Two**: On line 10 of the index.html, insert the following:
```js
require('electron-connect').client.create()
```

**Step Three**: In your CLI, type:
```sh
npm install electron-connect --save-dev
```
```sh
npm install -g gulp
```

**Step Four**: Begin the process by typing:
```sh
gulp serve
```

#### Jump to [Next Exercise](8-CYOA.md)
