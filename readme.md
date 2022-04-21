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

Either install the AUR package [`xfce-simple-dark`](https://aur.archlinux.org/packages/xfce-simple-dark/) or copy the files manually.


### Copying the files manually

#### Xfce widgets theme

Copy the folder `Xfce-Simple-Dark_widgets` to your `~/.themes/` directory.

#### Xfce window decoration theme

Copy the folders beginning with `Xfce-Simple-Dark_xfwm` to your `~/.themes/` directory. The different folders are for different sizes of the window decoration.

#### Geany theme

Copy the file `geany/simple-dark.conf` to `~/.config/geany/colorschemes/`.


### Activating the themes

#### Xfce widgets theme

Open the *Appearance* application (`xfce4-appearance-settings`) and select the theme.

#### Xfce window decoration theme

Open the *Window Manager* application (`xfwm4-settings`) and select the theme in the desired size.

#### Geany theme

In Geany, choose `View`, `Change color scheme...` and select the theme.


How to turn off auto-hiding of scrollbars
-----------------------------------------

Add the following line to the file `~/.xprofile` respectively `~/.profile` and reboot:

`export GTK_OVERLAY_SCROLLING=0`


How to turn off client side window decorations
----------------------------------------------

Install [`gtk3-nocsd`](https://github.com/PCMan/gtk3-nocsd).


License
-------

Xfce-Simple-Dark is FLOSS (free and open-source software).<br>
All files in this repository are licensed under the [GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0) (GPLv3).<br>
Copyright 2017-2022 Simon Krauter
