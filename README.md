# Historical abcjs Versions

This repository contains the deliverables for all the versions of [abcjs](https://github.com/paulrosen/abcjs)

## Types of deliverables

Multiple files have been delivered for different uses over the years. Here is how to decode the file names:

### Basic

In the early days, before SVG was standardized, raphael.js was a dependency and was bundled. This does not contain midi.js. In the early days, it did not include the interactive textarea.

#### abcjs_basic_VERSION-min.js

In the early days, this includes raphael.js and does not have audio or editing capabilities. 

#### abcjs_basic_noraphael_VERSION-min.js

In the early days, before SVG was standardized, raphael.js was a dependency and was bundled. If you didn't want the bundle use this.

#### abcjs_basic_midi_VERSION-min.js

This includes the dependency to midi.js and supports audio.

#### abcjs_midi_VERSION-min.js

Like the basic version but with a dependency on midi.js.

### Editor

This is like the basic version but includes the interactive editor in a textarea.

#### abcjs_editor_VERSION-min.js

This is like the basic version but includes support for an interactive textarea.

#### abcjs_editor_noraphael_VERSION-min.js

Like the editor without raphael.js.

#### abcjs_editor_midi_VERSION-min.js

Like the editor with a dependency on midi.js.

### Plugin

This is like the basic version except that it scans the page on page load looking for any text that is a well-formed abc string and automatically creates music.

#### abcjs_plugin_VERSION-min.js

In the early days, before SVG was standardized, raphael.js was a dependency and was bundled. This does not contain midi.js.

#### abcjs_plugin-nojquery_VERSION-min.js

The plugin required jquery. If it is already on the page then use this version to avoid two versions.

#### abcjs_plugin-midi_VERSION-min.js

Like the plugin version but with a dependency on midi.js.

#### abcjs_plugin_nojquery_VERSION-min.js

Like the plugin version but without jquery.

#### abcjs_plugin_noraphael_nojquery_VERSION-min.js

Like the plugin version but without raphael.js or jquery.
