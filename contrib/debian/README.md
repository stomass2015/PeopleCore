
Debian
====================
This directory contains files used to package peopled/people-qt
for Debian-based Linux systems. If you compile peopled/people-qt yourself, there are some useful files here.

## people: URI support ##


people-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install people-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your people-qt binary to `/usr/bin`
and the `../../share/pixmaps/people128.png` to `/usr/share/pixmaps`

people-qt.protocol (KDE)

