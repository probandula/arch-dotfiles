# Arch-Dotfiles
These are my early stage dotfiles for my Arch Linux system.  
I'm no Arch expert and it's possible that there are many mistakes in my dotfiles. Feel free to report these.

![screenshot](/other/screenshot.png)

```bash
git clone https://github.com/probandula/arch-dotfiles
cd arch-dotfiles
./install -h # Print help
```
**It's recommended to check first, if all software is installed (`./install -s`), then to manually backup your old configuration and then installing the dotfiles (`./install`).

### Software list
If you run `./install -s` there will be a list of software recommended or needed to use this configuration.
There is also printed if this software is currently installed on your system.  
**This list guarantees nothing and it's possible I forget something!**

### Environment variables
* **WALLPAPER**: The name (without extension) of the current wallpaper in the `~/.wallpapers` directory

### Scripts, functions and aliases

##### Misc
* **conf <key>**: Opens the specific config file for the given key (must be registered)
* **showkeys**: Shows the `sxhkd` configuration in a colored and more readable way
* **showcolors**: Shows the configured colors
* **ll**: Better file listing (`ls -la --color=auto`)
* **tree**: Better tree view (`tree -a -C -I ".git"`)
* **xterm**: Just a workaround for non bold font (`xterm -fm 5x10`)
* **set_bg <name>**: Sets the wallpaper by name (see $WALLPAPER)
* **update_bg**: Updates the background picture in case of resolution changes (Uses $WALLPAPER)
* **update_resolution**: Updates the screen resolution to `auto`
* **update_screen**: Calls `update_resolution` and `update_bg`
* **us**: Alias for `update_screen` (often needed in VirtualBox)

##### BSPWM aliases
* **bgap <int>**: Changes the window gap
* **bbw <int>**: Changes the border width
* **bnc**: Closes the current node

### Wallpapers
[Firewatch](http://blog.composanto.com/post/138965082204/firewatch-launch-wallpaper-when-we-redit-the)
