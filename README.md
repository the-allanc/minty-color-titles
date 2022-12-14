# minty-color-titles
This repository contains a gtk.css file which should provide coloured window headers for Linux Mint 21 Cinnamon (it may work with other DE's and other distros).

It's primarily configured to be integrated with both the Mint-X and Mint-Y themes (or any of their colour variants). The foreground and background colours for window headers (both active and inactive) can be manually overridden by modifying the defined colours at the top of the file. It's inspired by the [OneColor theme](https://www.gnome-look.org/p/1006952).

Applications which use [CSD](https://wiki.gnome.org/Initiatives/CSD) and don't have the standard window title should also be themed correctly (see the screenshots below).

## Usage

Just download the [gtk.css](../main/gtk.css?raw=true) file and save it to `~/.config/gtk-3.0/gtk.css`. Then restart Cinnamon.

## Description

The changes made:
* Active window header uses main foreground and background colours.
* No circular background for close icon.
* Hover-over for window actions (minimize, maximize etc.) will invert the background and foreground colours with a square background.
  * Clicking an action icon will change the background from square to a circle.

If you want the window icons to be a larger size (x1.5), then uncomment the section in the CSS file at the end which enables that.
  
## Screenshots:

### Hover-over actions

![Image](../main/screenshots/hover_example.gif?raw=true)

### Changing application theme

![Image](../main/screenshots/change_theme.gif?raw=true)

### Overriding theme colours manually

![Image](../main/screenshots/manual_colours.png?raw=true)

### Theming CSD applications

![Image](../main/screenshots/csd_app.png?raw=true)
