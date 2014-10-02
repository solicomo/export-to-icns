Export to ICNS
==============

A Sketch plugin which can export artboards or slice to ICNS.

It works both with the sandboxed (from App Store) and standalone versions of Sketch.

Installation
------------

1. Download [the latest ZIP file][1] of this plugin.
2. Extract a folder from the ZIP file and rename it to `Export to ICNS`.
3. Open Sketch plugins folder.
   
   You can access the Plugins folder easily by using the `Plugins › 
   Reveal Plugins Folder` menu option from Sketch.
   
4. Copy the folder `Export to ICNS` to the revealed plugins directory.

Usage
-----

### Export From Artboards

1. Create artboards by going to `File › New From Template › Mac App Icon` in the menu.
2. Design your icon on these artboards.
3. Choose `Plugins › Export to ICNS › From Artboards`.

>Note: You should not rename the artboards. You can prevent individual artboards from exporting by appending `Lock` to the name.

### Export From Slice

1. Design your icon on a single artboard.
2. Choose `Plugins › Export to ICNS › From Slice`.

>Note: The artboard should not be smaller than 1024x1024, or the hi-res icons will appear blurry.

Feedback
--------

If you have any trouble with this plugin, feel free to [open an issue][2].

Credits
-------

This plugin is a blend of existing technologies, and has very little original code in it. 
Here's what it uses:

+ [Generate ICNS][3], from [Nathan Rutzky](http://nath.co)
+ [Sketch Commands][4], from [Ale Muñoz](http://bomberstudios.com)

[1]: https://github.com/solicomo/export-to-icns/archive/master.zip
[2]: https://github.com/solicomo/export-to-icns/issues
[3]: https://github.com/NathanRutzky/Generate-ICNS
[4]: https://github.com/bomberstudios/sketch-commands

