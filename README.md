# dfix

Tool for automatically upggrading D source code

## Features

* Updates old-style alias syntax to new-style
* Fixes implicit concatenation of string literals
* Replaces uses of the catch-all syntax with an explicit ```catch (Throwable)```
* Upgrades code to comply with DIP64 when the ```--dip64``` switch is specified.
* Upgrades code to comply with DIP65 when the ```--dip65``` switch is specified.

## Planned Features

* Automatic conversion of C-style array declarations and parameters to D-style.

## Notes

dfix will edit your files in-place. Do not use dfix on files that have no
backup copies. Source control solves this problem for you. Double-check the
results before checking in the modified code.
