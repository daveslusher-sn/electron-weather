**Step One**: Anywhere in your command line, type:
```sh
npm install -g electron-packager
```
**Step Two**: Then, from your branch on the CLI:
```sh
electron-packager .
```

**Step Three**: On line 20 of package.json, add a comma:
```js
"electron": "^1.6.8",
```

**Step Four**: On line 21 of package.json, add:
```js
"electron-packager": "^8.7.0"
```

**Step Five**: Commit your changes.


### Troubleshooting Steps
There might be some inconsistencies between electron-packager and the most recent version of node. If the steps above didn’t work for you, try using node 6.11.2 with npm 3.10.10. The following steps should help you do this on macOS.

Note: We’re using nvm here instead of n, or other version manager tools. If you can duplicate successful steps to adjust your node version, please do so (and good luck!).

macOS

**Step One**
```
brew cask install xquartz
```
**Step Two**
```
brew install wine
```
**Step Three**
```
Type brew install nvm
```
**Step Four**
```
nvm install 6.11.2
```
**Step Five**
```
nvm use 6
```
**Step Six**
```
npm run build
```
WARNING – It might take a long time to build the win32 package. Leave this for 5-10 minutes and return.

### Jump to [Next Exercise](6-packaging-extensions.md)
