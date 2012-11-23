---
layout: release
title: Version 1.4.0 released
excerpt: Details of the 1.4.0 release
tags: [releases, 1.4.0]
categories:
    - releases
---
## Version 1.4.0

It's finally here! Version 1.4.0 has been released. Thanks to everyone who contributed!

There has been lot of improvements to the BBCode parser in this version, including better support for custom self closing tags and different BBCode dialects.

**Important** This version is *not* backwards compatible with previous versions. Some functions have been removed/renamed plus the default BBCode dialect has changed slightly.

As much as I hate breaking backwards compatibility these updates really needed doing. Hopefully it will be a long time before any more non-backwards compatible changes will need to be done.

### Full 1.4.0 changelog:

 * New theme "square" added
 * Some none-backwards compatible tidying:  
   All occurrences of `textEditor` have been changed to `sourceEditor`  
   `updateTextareaValue` has been changed to `updateOriginal`  
   `destory` has finally been renamed to `destroy`  
   Removed the deprecated `setCommand` and `commandExists` functions.
 * Added resizeWidth and resizeHeight options to allow disabling of either width or height resizing while keeping the other
 * Improved resize handling
 * Updated build.php
 * Fixed bug with emoticons containing backslashes. - Thanks to emanuele45 for the fix.
 * Fixed bug when pasting from Word. - Thanks to @Spuds for reporting.
 * Fixed bug causing scrollbar to change when inserting BBCode in source mode. - Thanks to Martec for reporting
 * Fixed bug causing cursor position to be lost in FF when getting the editors value. - Thanks to @Spuds for reporting
 * Improve IE support
 * Moved roadmap from GitHub wiki to source directory for easier editing.
 * Added a new much more flexible BBCode parser
 * Added new option to auto-update original textbox on blur event occurring on SCEditor. - Thanks to @maiiku for adding this feature
 * Updated sceditor() to return the instance/instances of the editor by passing "instance" to sceditor() and protect against re-initialization. - Thanks to @maiiku for reporting
 * Updated sceditor() to return the current state of the editor by passing state to sceditor(). - Thanks to @maiiku
 * Added IE 10 support
 * Added Vietnamese translation. - Thanks to Chien for translating
 * Added plugins option - Thanks to @maiiku
 * Updated editor to force new line after code and quote tags so that text can be entered after them. - Thanks to Logan
