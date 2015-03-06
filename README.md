# Robothon 2015 Samples

These are the plugins I coded on stage at [Robothon 2015](http://robofab.com/robothon/). After installation, they will add the menu items *View > Show Bounds* and *Filter > Random Rotate*. You can set keyboard shortcuts in System Preferences.

In case you saw the live stream (or are watching the recording later), the second example didn’t work out live on stage because I forgot to compile my .xib to a .nib. If you wonder what that is, it is explained in the Readme of the [GlyphsSDK](https://github.com/schriftgestalt/GlyphsSDK) and in the step-by-step instructions inside the comments of the .py files.

### Installation

1. Download the complete ZIP file and unpack it, or clone the repository.
2. Double click the .glyphsReporter and .glyphsFilter file. Confirm the dialogs that appear in Glyphs.
3. Restart Glyphs

### Show Bounds Usage Instructions

1. Open a glyph in Edit View.
2. Use *View > Show Bounds* to toggle the display of the bounding box with flashing colors.

### Random Rotate Usage Instructions

1. Select one or more glyphs in Edit or Font View.
2. Use *Filter > Random Rotator* to bring up the dialog and randomly rotate your glyph(s).

Or:

1. Go into *File > Font Info > Instances*.
2. Add a *Filter* custom parameter
3. Insert *RandomRotate;10* as parameter value. Replace the number 10 with whatever maximum rotation angle you want to employ.
4. Export your font.

### Requirements

The plugins were only tested in [Glyphs 2.0](http://glyphsapp.com/beta). I don’t know if they work anywhere else.

### License

Copyright 2015 Rainer Erich Scheichelbauer (@mekkablue).
Based on sample code by Georg Seifert (@schriftgestalt).

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

See the License file included in this repository for further details.
