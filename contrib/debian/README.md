
Debian
====================
This directory contains files used to package nextond/nexton-qt
for Debian-based Linux systems. If you compile nextond/nexton-qt yourself, there are some useful files here.

## nxton: URI support ##


nexton-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nexton-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nextonqt binary to `/usr/bin`
and the `../../share/pixmaps/nexton128.png` to `/usr/share/pixmaps`

nexton-qt.protocol (KDE)

