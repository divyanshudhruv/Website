⚠️Breaking Changes:

Disabled rendering of MathML elements.
🌵Feature

Added support for SPARQL and Turtle languages (@vemonet).
Added support for forward navigation in table cells with Shift+Tab (@evan-cohen).
Added support for negative zoom.
Adjusted footnote inline code font size.
Added shortcut to toggle table of contents panel (@zmen).
Added settings option to disable HTML rendering.
Added support for a relative image directory.
Added support to include table of contents in exported document.
🦋Optimization

Improved color of word counter in graphite light theme (@bmvisoky).
Improved UX of font selection.
🪲Bug fix

Fixed XSS security vulnerability when parsing MathML submitted by @0xBADCA7.
Fixed an issue that URLs with trailing slashes are not recognized (@sweetliquid).
Fixed closing tabs with mouse-middle click (@mnxn).
Fixed an exception when selecting a table cell with Ctrl+A (@AmauriAires).
Fixed quick open searcher (@munckymagik).
Fixed code highlighting in a special case (@zmen).
Fixed an issue with shaking in typewriter mode (@MrHeer).
Fixed spell checker config schema violation on Windows and allowed BCP-47 language codes.
Fixed behavior when a single table cell is selected.
Fixed an issue that symbolic files could not be opened.
Fixed blank window when opening a second window with --new-window.
