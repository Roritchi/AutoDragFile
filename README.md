# AutoDragFile

> :warning: Only works under X11!

Small python script that helps you drag files programatically

After running the Script, a GTK Window gets created right under your cursor's position,
if you dont start the drag process within 3 seconds, the program exits.
After starting the drag process, the program exits after 10 seconds,
you need to have finished the drag process until then, because the drag process will cancel
once the process is stopped.

UI Text is in German, but its just 2 Words.

## Usage
```
python3 drag.py /path/to/file
```

## Dependencies
* xdotool
* python-gobject
* gtk3

Arch / Manjaro:
```
pacman -Sy xdotool python-gobject gtk3
```
