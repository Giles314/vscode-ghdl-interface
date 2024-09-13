# Changelog

## VHDL-Wave

### version 1.0.0 - 08.09.2024

* Name and maintainer change
* Bugs fixed around setup and folders probably link to obsolescence
* Submenu for editor and explorer context menus to avoid cluterring menus

## GHDL-Interface

### Version 1.1.2 - 23.07.2020

* New feature: Set GHDL options in User/Workspace settings

### Version 1.0.2 - 04.07.2020

* Bugfix: changed all occurences of `resourceExtname == vhdl` to `resourceExtname == .vhdl` to recognize the ".vhdl" file extension

### Version 1.0.1 - 16.04.2020

* Added GHDL functions
  * GHDL elaborate
  * GHDL run unit (export to .ghw file)
  * GHDL clean
  * GHDL remove
* GHDL functions can now be invoked from the explorer
* Added keybindings (for more details see README)
* Shows full error message in Toast
* Implemented GTKWave invokation function (only available in explorer)

### Version 0.0.1 - 1.4.2020

* Initial release
* Implemented basic functionality: 
  * Analyze files with ghdl 
  * Highlight reported errors in editor
* Keybindings (for analyze file):  
  * Windows: cntrl + alt + a
  * Mac: shift + cmd + a
  * Linux: shift + alt + a 