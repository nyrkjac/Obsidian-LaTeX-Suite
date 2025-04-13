# Obsidian-LaTeX-Suite

This is my custom settings for the Obsidian plugin "LaTeX-Suite". Simply copy the text inside the .js file and paste in into the snippets section in the plugins settings within Obsidian's app settings. This data is usually stored in the data.json file but since Github had some issues with uploading this file, I chose to make it available as a .js file with the added benefit of neat syntax highlighting.

# Changes from the original file:
Additions for easier math:
- `mq`,`$ + Tab` for inline math mode
- `bm + Tab`,`$$` for block math mode
- `^ + Tab` for superscript
- `over + Tab`,`under + Tab` for `\overset`,`\underset` respectively
- `{}` can now be navigated with `Tab`
- `vv` for `\vec{}`
- `..` for `\dots`
- `v..` for `\vdots`
- `c.` for `\cdot`
- `<-->`, `<=>`,`<==>`,`->`,`-->` for different arrows
- `KK`,`QQ`,`EE` to put these letters into the `mathbb` environment

commands that don't activate without `Tab` 
- `rd`,`_` for super-/subscript respectively
- `und` for `underline`
- `<>` for `<$0>$1</$0>$2` to use html-tags
- `abs` for `||`

deleted commands:
- `mk` for inline math
- `dm` for block math
