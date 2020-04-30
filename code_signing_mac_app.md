![trash.png](https://bitbucket.org/repo/yprLRxE/images/2480692657-trasher.jpg)

* launch `Terminal`
* `xattr -cr /Applications/imhicihu-biblio.app`
---------
* check this issue on [code-signing](https://github.com/electron/electron/issues/20027)
* [Codesigning Electron Applications](http://jbavari.github.io/blog/2015/08/14/codesigning-electron-applications/)
* If have issues in the codesign step when running `yarn run package`, you can temporarily disable code signing locally by setting export `CSC_IDENTITY_AUTO_DISCOVERY=false` for the current terminal session.