![trash.png](https://bitbucket.org/repo/yprLRxE/images/2480692657-trasher.jpg)

* launch `Terminal`
* `xattr -cr /Applications/imhicihu-biblio.app`
---------
* check this issue on [code-signing](https://github.com/electron/electron/issues/20027)
* [Codesigning Electron Applications](http://jbavari.github.io/blog/2015/08/14/codesigning-electron-applications/)
* If have issues in the codesign step when running `yarn run package`, you can temporarily disable code signing locally by setting export `CSC_IDENTITY_AUTO_DISCOVERY=false` for the current terminal session.
---------
* Use an internet browser to go to the Releases section at https://github.com/imhicihu/BiblioSearcher/releases
* If you're using a Mac OSX, click on BiblioSearcher-darwin-x64.zip to download it to your `Downloads` folder.
* Unzip the file by double-clicking on the zip file.
* In Finder, navigate into the `BiblioSearcher-darwin-x64` folder.
* Click Finder menu `File`, `New Finder` window.
* In that new window, click menu `Go`, then `Applications`.
* Drag Git-it and drop it into the Applications files.
* Hold down the `control` key on your keyboard and click `BiblioSearcher` for the context menu:
* `BiblioSearcher` open
* Click `Open`.
* Click `Open` to confirm the warning:
* The `BiblioSearcher` welcome screen should appear
---------
* Note that `BiblioSearcher` is an "unsigned application", so later versions of macOS will ask for extra confirmation the first time you run it.

---------
* The Catalina macOS download is notarized and uses the "hardened runtime," which may reduce compatibility with certain modules. You may still run the regular 64-bit macOS download on Catalina; however, you must right click and choose `Open` when running that version for the first time.

---------
* [Notarizing Your App](https://samuelmeuli.com/blog/2019-12-28-notarizing-your-electron-app/)
---------