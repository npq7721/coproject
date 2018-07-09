
Debian
====================
This directory contains files used to package coralliumd/corallium-qt
for Debian-based Linux systems. If you compile coralliumd/corallium-qt yourself, there are some useful files here.

## corallium: URI support ##


corallium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install corallium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your coralliumqt binary to `/usr/bin`
and the `../../share/pixmaps/corallium128.png` to `/usr/share/pixmaps`

corallium-qt.protocol (KDE)

