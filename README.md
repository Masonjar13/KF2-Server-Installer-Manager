# KF2 Server Installer + Manager

Recently made my own KF2 server, and it was a bit of a pain figuring it all out for the first time. So, I made a simple installer. Still working on the manager (had to rewrite it twice for reasons).

As soon as it runs, it will start installing it to the current directory\ `baseDir` . As per requirement, it downloads steamcmd, extracts, auto-updates on run, and downloads/installs the KF2 server files to `serverDir` . After it's finished downloading, it immediately enables the WebAdmin interface (it's off by default). On subsequent runs (when the directories are the same), it will perform an update on the server. If the game updates, it's very likely the server will have to update as well to continue running properly.

The manager will be similar to my Syncthing manager; it will mostly be a tray menu, with quick access to the WebAdmin interface and std output. Pretty much all you need, the WebAdmin has everything you'll need for anything else. I'll add instructions for adding custom maps, maybe some automation since it's just ini files to deal with.

For the less savvy, I'll be posting binaries as well.
