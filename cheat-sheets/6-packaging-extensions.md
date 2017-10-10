**Step One**: From your project's root directory:
```sh
mkdir Icons
```
**Step Two**: Find an icon, here: https://useiconic.com/open

**Step Three**: Convert that icon into three filetypes, using this site: https://iconverticons.com/online/
- macOS - .icns
- Windows - .ico
- Linux - .png

**Step Four**: Add each image to the Icons directory.

**Step Five**: Replace the previous build script in your package.json to account for builds with different icons with the scripts below. In the example below, the app name is electron-app, and the icon name is unicorn. You can change that to match your own app and icon name.
```
"build-darwin"  : "electron-packager . electron-app --platform=darwin --icon Icons/unicorn.icns --overwrite",
"build-mas"     : "electron-packager . electron-app --platform=mas --icon Icons/unicorn.icns --overwrite",
"build-linux"   : "electron-packager . electron-app --platform=linux --icon Icons/unicorn.png --overwrite",
"build-win32"   : "electron-packager . electron-app --platform=win32 --icon Icons/unicorn.ico --overwrite",
"build"         : "npm run build-darwin && npm run build-mas && npm run build-linux && npm run build-win32"
```
**Step Six**:
```
npm run build
```

#### Jump to [Next Exercise](7-refresh.md)
