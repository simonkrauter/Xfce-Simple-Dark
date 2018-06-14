Xfce-Simple-Dark
===============

Xfce-Simple-Dark is a dark theme for Xfce and Geany.<br>
It contains styles for widgets and window titles.

The GTK 2.x and GTK 3.0 widget theme is based on https://github.com/vkuzel/Xfce-darkness .<br>
The GTK 3.20 widget theme is based on https://github.com/horst3180/vertex-theme .<br>
The window title theme is based on Makulu Black.

Screenshot
------------

<a href="https://github.com/trustable-code/Xfce-Simple-Dark/blob/master/screenshot.png"><img src="https://raw.githubusercontent.com/trustable-code/Xfce-Simple-Dark/master/screenshot.png" width="500"></a>

Installation
------------

1. Copy theme folder `Xfce-Simple-Dark` into your `~/.themes/` directory.
2. Open *Appearance* and select the theme.
3. Open *Window Manager* and select the theme.
4. To use the theme for Geany, copy files from directory `geany` to `~/.config/geany/colorschemes/`

How to turn off auto-hiding of scrollbars
-----------------------------------------

Add the following line to the file `~/.xprofile` respectively `~/.profile` and reboot:

`export GTK_OVERLAY_SCROLLING=0`

License
-------

Xfce-Simple-Dark is FLOSS (free and open-source software).<br>
All files in this repository are licensed under the [GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0) (GPLv3).<br>
Copyright 2017 Simon Krauter
