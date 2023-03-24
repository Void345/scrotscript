# scrotscript
a little script i made to take screenshots how i want them to be taken:
- save image named with unix timestamp 
- copy image to clipboard

by default outputs to ~/Pictures/screencap (it doesn't create this directory)

requires copyq, scrot, notify-send (script uses sw-notify-send cuz gentoo i think idk edit it urself)

intended to be bound with your hotkey manager

`scrotscript` takes a screenshot of the whole screen

`scrotscript -r` takes a screenshot of a region picked with your mouse

`scrotscript -a` takes a screenshot of the active window
these are just normal scrot settings but i changed the letters because the scrot ones don't make sense :3
