<p align="center">
  <img src="https://user-images.githubusercontent.com/3791941/31036931-072760fe-a534-11e7-8cd7-0565bdc2727c.png" width="100" height="60">

  <h3 align="center">Electron: Start to Finish<br></h3>
</p>

**What This Session is About**

Getting up and running on [Electron](https://electron.atom.io/), a framework to build cross platform desktop apps with JavaScript, HTML, and CSS. You'll walk away with a fully functional Electron desktop app that you can take apart and customize, along with the knowledge to confidently start building your own Electron apps. This repository houses a series of introductory-to-intermediate exercises to Git familiar with Electron by manipulating and extending a prebuilt weather app.

**Summary**

Built with the [photon](http://photonkit.com) user interface kit.
Uses the [Dark Sky Forecast API](https://developer.forecast.io) as a data source.

**Table of Contents**
- [Prerequisites](#prerequisites)
- [Cheat Sheets](#cheat-sheets)
- [End Product](#end-product)
- [Resources](#extended-resources)

## Prerequisites

- [Install Git](#install-git)
- [Get familiar with Git commands](#get-familiar-with-git-commands)
- [Install a text editor](#install-a-text-editor)
- [Install Node.js](#install-nodejs)

#### Install Git

##### macOS
Mac users, while you probably already have _a_ version of Git on your system, it may be out-of-date. You can [download an updated installer package here](https://git-scm.com/download/mac).


Advanced users might consider installing the latest stable version of Git with [Homebrew](https://brew.sh), e.g.: 
  ```sh
  brew install git
  ```

##### Windows
[Git for Windows](https://git-for-windows.github.io/) provides both Git and a Bash emulation environment to use Git on the command line.

##### Linux
While some Linux distributions come with a version of Git installed, it's often out-of-date. [This guide](https://git-scm.com/download/linux) has recommended commands to install Git with your distribution's preferred package manager.

##### Get familiar with Git commands
You'll want to know how to [fork](https://help.github.com/articles/fork-a-repo/) and [clone](https://help.github.com/articles/cloning-a-repository/) a Git repository, and how to [check out a branch](https://git-scm.com/docs/git-checkout#git-checkout-emgitcheckoutemltbranchgt).

If you need a refresher, consider [exploring our free on-demand training](https://services.github.com/on-demand/).

#### Install a text editor
Perhaps consider [Atom](https://atom.io/) if you're looking for an awesomely hackable text editor for the 21st century!

#### Install Node.js
> **Q:** Why do we need to install Node.js if Electron includes Node.js?
>
> **A:** While Electron does include its own internal version of Node.js, what we'll install first includes `npm`, the Node Package Manager. NPM is what powers our dependency installation and build processes.

For all platforms, visit [nodejs.org](https://nodejs.org/en/download/) to download the installer package. For our purposes today, we recommend the "LTS" package.

For advanced users: if you later want to install multiple versions of node and npm on your system you can use tools like [`nvm`](https://github.com/creationix/nvm) or [`n`](https://github.com/tj/n).

Once you've got Node.js installed you will have the `node` and `npm` commands available in your terminal. You should be able to `npm install` packages now, without using `sudo`. If you see errors when installing packages with npm, you may need to [fix your permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions).

## Cheat-Sheets
The cheat sheets for each activity are linked here:

- [Exercise 1: Getting Started](cheat-sheets/1-getting-started.md)
- [Exercise 2: Diving In](cheat-sheets/2-diving-in.md)
- [Exercise 3: Electron Defaults](cheat-sheets/3-electron-defaults.md)
- [Exercise 4: Refactoring](cheat-sheets/4-refactoring.md)
- [Exercise 5: Packaging](cheat-sheets/5-packaging.md)
- [Exercise 6: Packaging Extensions](cheat-sheets/6-packaging-extensions.md)
- [Exercise 7: Refresh](cheat-sheets/7-refresh.md)
- [Exercise 8: CYOA](cheat-sheets/8-CYOA.md)

## End Product
At the end of all of our exercises, you should have an app that looks similar to this!
![screenshot](https://cloud.githubusercontent.com/assets/671378/15033544/97011f38-1220-11e6-9611-1571063fe107.png)

## Extended Resources
https://github.com/universeworkshops/electron-weather/issues/1
