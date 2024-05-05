# dotfiles
A small portion of dotfiles that I put together, using multiple dotfiles as inspiration. The dotfiles can be considered a bit buggy for some setups, as it is fairly old.

What's included?
> A wallpaper that fits fairly well with the colorpalette.
> A script to launch sway with dbus, recommended to put in /usr/local/bin for compatibility (systemd users should pay attention due to merged-usr)
> screenshots
> Rather basic config, which works fine. Built upon the vanilla one as it is good for what it is and for my workuse.
> Kitty config
> Mako (notif) daemon config, which *should* fit with the color palette.
> A script for waybar that allows you to visualize as it listens in dbus.

dependencies:
 waybar, atleast 0.9.24
 mako for the notifications
 cava for the visualizer on the bar
 sway
 kitty, config for the color palette is included here.
 wlogout, minor configuration required if you have systemd. dotfiles are made in gentoo with OpenRC init system. Stock theme, so you can go wild here.
 Pipewire to make sure that cava works
 swww for images, as it can change them on the spot with a cool animation, not requiring a WM restart.
