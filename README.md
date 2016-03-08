# RichTextFormat
Syntax highlighting for RTF files in Sublime Text 3.

## Features

- Syntax highlighting for RTF files including:
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

1. [Ensure Package Control is installed.](https://packagecontrol.io/installation)
1. In Sublime Text, open the `Preferences` menu, and select `Package Control`.
1. Select `Package Control: Install Package`.
1. Start typing `RichTextFormat`. When you see it, select it.
1. Wait for it to install.
1. Re-open any open RTF files, or set their syntax to RTF manually.
1. Enjoy!

## Potential Future Improvements

- integrate with the awesome BracketHighlighter plugin to ensure that parenthesis don't affect curly brace matching.
