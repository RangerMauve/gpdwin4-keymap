# gpdwin4-keymap

My keymap for the GPD Win 4 using the gpdconfig cli utility

# Why?

I'm not satisfied with the default key mappings.
I had a fancy setup for my steam deck and the muscle memory loss was painful when switching.
I want to be able to do keyboard shortcuts without needing to stretch accross the physical keyboard.
I want to do some basic window manager navigation entirely with the controller controls.
I wish this thing had stuff like "double press" bindings the way I could with my steam deck. 🤷

# How to use

- update your GPD Win 4 firmware
- install [gpdconfig](https://github.com/RangerMauve/pyWinControls) somewhere in your path
- `sudo gpdconfig -s ./config.txt`

Bam!

# What it does:

- right trigger is primary mouse, left secondary
- left bumper is ctrl
- right bumper is shift
- left back button is alt
- right back button is meta/super
- left analog is arrow keys
- clicking it is tab
- right analog is still the mouse, cicking it enables "fast mouse"
- dpad left is "page up", dpad right is "page down"
- select is "copy", start is "paste", some apps might need to be configured to properly detect these keys
- menu in the bottom right is middle click

---

Feel free to fork and customize according to your needs.
Feel free to open a "discussion" on this repo to talk about your config for others to find.
