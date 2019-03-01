
Debian
====================
This directory contains files used to package muusicd/muusic-qt
for Debian-based Linux systems. If you compile muusicd/muusic-qt yourself, there are some useful files here.

## muusic: URI support ##


muusic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install muusic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your muusicqt binary to `/usr/bin`
and the `../../share/pixmaps/muusic128.png` to `/usr/share/pixmaps`

muusic-qt.protocol (KDE)

