# awesome-config
My awesome wm rc.lua configuration file.

It makes several changes to the default configuration, including..

* Removes the top bar
* Removes all tags except one
* Removes window decorations
* Comments out all layouts besides fair, fairv, and floating
* Changes the run keybinding to execute dmenu_run
* Changes the default 24hr clock to 12hr
* Changes terminal to xfce4-terminal
* Changes default editor to vim
* Starts picom on startup
* Starts xscreensaver on startup
* Starts feh on startup to set the wallpaper (located in ~/wallpapers/bg.jpg)

You'll probably have to change out mentions of my username ("dominik") for your own if you wish to run this yourself.
This config is known to work with awesome 4.3 on FreeBSD - I cannot guarantee compatibility with any other version.

You'll also need these packages installed if you want to run this:
```
dmenu xfce4-terminal picom vim feh
```
