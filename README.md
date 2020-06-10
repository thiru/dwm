# Thiru's build of dwm

[dwm](https://dwm.suckless.org/) is a minimalist tiling window manager for Linux.

## FAQ

1. This isn't a fork because the [upstream repo](https://git.suckless.org/dwm) is not on Github.

1. The structure of this repo was originally based on [this guide](https://dwm.suckless.org/customisation/patches_in_git/). The changes I made are mostly around making it easier for Github users.

1. The **master** branch contains my current build of dwm with all the patches and customisations merged.

1. The **upstream** branch follows suckless' **master** branch.

1. Branches that start with **patch-** are based on ["official" patches](https://dwm.suckless.org/patches/) available as source on the suckless website.

## Dependencies

* [alacritty](https://github.com/alacritty/alacritty)

## Patches

* [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/)
  * Make windows full-screen
  * `mod + shift + f`
* [autostart](https://dwm.suckless.org/patches/autostart/)
  * Ability to specify user scripts when starting dwm
  * changed autostart scripts path from `~/.dwm` to `~/.config/dwm`
* [centeredmaster](https://dwm.suckless.org/patches/centeredmaster/)
  * A popular layout with the focus in the middle of the screen
* [fullgaps](https://dwm.suckless.org/patches/fullgaps/)
  * Pretty gaps between windows
  * `mod + =` increase gap
  * `mod + -` decrease gap
  * `mod + shift + =` remove gaps
* [restartsig](https://dwm.suckless.org/patches/restartsig/)
  * Restart dwm without logging out (to update source)
  * `mod + ctrl + shift + q`
* [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
  * A persistent terminal scratchpad that can be easily brought in and out
  * `mod + s`
    * (default was `mod + tilde`)
  * changed terminal to `Alacritty`
* [shiftview](https://dwm.suckless.org/patches/nextprev/)
  * Cycle through tags
  * `mod + shift + h` go to left tag
  * `mod + shift + l` go to right tag
* [sticky](https://dwm.suckless.org/patches/sticky/)
  * Ability to stick window so it appears in all tags
  * `mod + shift + s`
    * (default was `mod + s`)

## Credits

Thanks to [Luke Smith's build](https://github.com/lukesmithxyz/dwm) as this is originally based on it.
