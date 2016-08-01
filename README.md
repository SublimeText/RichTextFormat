# RichTextFormat
Syntax definition for RTF files in Sublime Text 3, so they can be highlighted by your color scheme.

## Features

- Syntax definition for RTF files, so that the following can be highlighted by your color scheme:
  - braces
  - control words
  - numeric parameters
  - control symbols
  - bookmarks
  - fields
  - special characters

Also it is possible to see the bookmarks in the document, and jump to them, using Sublime Text's Goto Symbol functionality.

![Syntax highlighting and Goto Symbol in action](https://cloud.githubusercontent.com/assets/11882719/13594131/872688f2-e50a-11e5-9c20-f2528ec82a61.gif "A demonstration of the RTF syntax highlighting and Goto Symbol (bookmark) functionality.")

## Installation

The recommended way to install the Sublime Text RTF syntax is via [Package Control](https://packagecontrol.io/packages/RichTextFormat). Package Control will install the plugin on your system and keep it up to date.

0. [Ensure Package Control is installed.](https://packagecontrol.io/installation)
0. In Sublime Text, open the `Preferences` menu, and select `Package Control`.
0. Select `Package Control: Install Package`.
0. Start typing `RichTextFormat`. When you see it, select it.
0. Wait for it to install.
0. Re-open any open RTF files, or set their syntax to RTF manually.
0. Enjoy!

## Color Scheme - Scopes

This package follows the conventions set out in the [official ST3 scope naming documentation](http://www.sublimetext.com/docs/3/scope_naming.html).
Some color schemes won't color punctuation by default, so you may want to tweak it or request that the author of the color scheme tweak it - because there aren't many distinct token types in RTF files, and braces are important - highlighting them in a different color can make the documents much more readable!

Scopes:

- `text.rtf punctuation.section` curly braces (`{`)
- `text.rtf punctuation.separator` semi-colons (`;`)
