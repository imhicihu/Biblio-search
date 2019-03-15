## Pros and Cons of Using SQLite with Electron
Just like the previous approaches, Using SQLite with Electron has some pros anc cons. Lets start with the pros:

SQLite can be bundled with your Electron app so the end user doesn't need to install anything beside your application.
SQLite Doesn't get in the way for Electron cross platform feature since it's available for all platforms that Electron target (Windows, Linux and MAC).
Suitable for small as medium projects.
Except for rebuilding gotchas, SQLite can be easily integrated and used with Electron.

Now lets look at the cons:

SQLite is a native module so it needs to be recompiled before it can be used with Electron.
To target different architectures you need to rebuild SQLite for each possible architecture.

(from https://www.techiediaries.com/electron-data-persistence/)