* The directory string must end with appropriate slashes, forward slash for unix and back slash with escape string for Windows) (e.g. Windows: ```'C:\\databases\\'```, Unix: ```'/Users/<username>/Desktop/'```). For good practice, use the ```path.join``` method to let the OS apply its directory separator automatically.
* When distributing your packaged app, you have to also ship the `locales` folder