
Debian
====================
This directory contains files used to package sprocketd/sprocket-qt
for Debian-based Linux systems. If you compile sprocketd/sprocket-qt yourself, there are some useful files here.

## sprocket: URI support ##


sprocket-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sprocket-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sprocketqt binary to `/usr/bin`
and the `../../share/pixmaps/sprocket128.png` to `/usr/share/pixmaps`

sprocket-qt.protocol (KDE)

