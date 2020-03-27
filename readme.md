Xfce-Simple-Dark
================

Xfce-Simple-Dark is a set of dark themes for:
- Xfce widgets,
- Xfce window decoration and
- Geany.<br>

The GTK 2.x and GTK 3.0 widget theme is based on https://github.com/vkuzel/Xfce-darkness .<br>
The GTK 3.20 widget theme is based on https://github.com/horst3180/vertex-theme .<br>
The window decoration theme is created from scratch. It exists in different sizes of the window decoration to support HiDPI environments.


Screenshot
------------

<a href="https://github.com/trustable-code/Xfce-Simple-Dark/blob/master/screenshot.png"><img src="https://raw.githubusercontent.com/trustable-code/Xfce-Simple-Dark/master/screenshot.png" width="700"></a>


Installation
------------

### Xfce widgets theme

1. Copy the folder `Xfce-Simple-Dark_widgets` to your `~/.themes/` directory.
2. Open the *Appearance* application (`xfce4-appearance-settings`) and select the theme.

### Xfce window decoration theme

1. Copy the folders beginning with `Xfce-Simple-Dark_xfwm` to your `~/.themes/` directory. The different folders are for different sizes of the window decoration.
2. Open the *Window Manager* application (`xfwm4-settings`) and select the theme in the desired size.

### Geany theme

Copy the file `geany/simple-dark.conf` to `~/.config/geany/colorschemes/`.


How to turn off auto-hiding of scrollbars
-----------------------------------------

Add the following line to the file `~/.xprofile` respectively `~/.profile` and reboot:

`export GTK_OVERLAY_SCROLLING=0`


License
-------

Xfce-Simple-Dark is FLOSS (free and open-source software).<br>
All files in this repository are licensed under the [GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0) (GPLv3).<br>
Copyright 2017-2020 Simon Krauter
