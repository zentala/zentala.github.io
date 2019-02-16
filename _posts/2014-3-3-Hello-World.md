---
layout: post
title: TeamViewer in console (CLI), without GUI
---

I just figured out that is possible to use TeamViewer without GUI, in pure console mode. Sometimes that may be helpfull if you need to get easy access to a remote server, that is located behind NAT. 

```$ cd ~/Downloads/
$ wget https://download.teamviewer.com/download/linux/teamviewer_i386.deb
$ sudo dpkg -i teamviewer_i386.deb
$ teamviewer help                            # list of commands, but not all of them, I don't know why
$ teamviewer info                            # check TV daemon status and get TV ID
$ sudo teamviewer passwd [password]          # set new password```

If u want save space u can also install `TeamViewer Host`.
