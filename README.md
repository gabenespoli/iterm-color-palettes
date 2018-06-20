# iTerm Colour Palettes

This is a collection of 16-colour terminal palettes that I have gathered and/or modified from other colour schemes. I consider the colour *scheme* to be how these 16 colours are applied to different syntaxes, whereas the *palette* is the colours themselves. These are just the palettes, and they are meant to be used with either [Base16](http://chriskempson.com/projects/base16/) or [Solarized](http://ethanschoonover.com/solarized) colour schemes. That is, the 16 terminal colours are arranged in the following way:

| Terminal Colour Code | base16 Colour Code            | Solarized Colour Code |
| -------------------- | ----------------------------- | --------------------- |
| Colour 0             | base00 (default background)   | Base02                |
| Colour 1             | base08 (red)                  | Red                   |
| Colour 2             | base0B (green)                | Green                 |
| Colour 3             | base0A (yellow)               | Yellow                |
| Colour 4             | base0D (blue)                 | Blue                  |
| Colour 5             | base0E (purple)               | Pink                  |
| Colour 6             | base0C (cyan)                 | Cyan                  |
| Colour 7             | base05 (default foreground)   | Base2                 |
| Colour 8             | base03 (comments)             | Base03 (background)   |
| Colour 9             | base09 (orange)               | Orange                |
| Colour 10            | base01 (lighter background)   | Base01                |
| Colour 11            | base02 (selection background) | Base00                |
| Colour 12            | base04 (dark foreground)      | Base0 (foreground)    |
| Colour 13            | base06 (light foreground)     | Purple                |
| Colour 14            | base0F (pink^*^)              | Base1                 |
| Colour 15            | base07 (light background)     | Base3                 |

^*^Base16 colour 0F is deprecated according to the website, but it is traditionally used for brown. In these palettes, I use this colour for pink.

For dark colour palettes, base16-base00/Solarized-Base03 is dark and base16-base07/Solarized-Base3 is light; for light colour palettes the order is reversed. This means you can switch the colour palette without having to change the underlying colour scheme. There are 8 colours and 8 greys, and are conceptually organized in the following way. Note that while the Solarized colourscheme is reversible, base16 is not due to its preference for more tones between the default background and foreground. Also, some of these colour palettes come from existing schemes that do not conform to this arrangement. For these I have had to pick and choose from the available colours, and in some cases tweak or even create colours.

| Function                          | base16 | Solarized  |
| --------------------------------- | ------ | ---------- |
| background (main)                 | base00 | Base03     |
| background (status bars)          | base01 | Base02     |
| background (selection)            | base02 |            |
| foreground (comments)             | base03 | Base01     |
| foreground (darker)               | base04 | Base00     |
| foreground (main)                 | base05 | Base0      |
| foreground (lighter)              | base06 | Base1      |
| foreground (bright)               | base07 | Base2      |
| foreground (brighter)             |        | Base3      |
| Red                               | base08 | Red        |
| Orange                            | base09 | Orange     |
| Yellow                            | base0A | Yellow     |
| Green                             | base0B | Green      |
| Cyan                              | base0C | Cyan       |
| Blue                              | base0D | Blue       |
| Purple                            | base0E | Purple     |
| Pink                              | base0F | Pink       |

iTerm requires a few other colours to be specified other than the 16 terminal colours. In most cases they have the following values. Note that selected text differs between the two colorschemes: for base16 the selection background is used, whereas for Solarized the selected text is reverse.

| Colour        | base16               | Solarized            |
| ------------- | -------------------- | -------------------- |
| Foreground    | base05 (terminal 7)  | Base0  (terminal 12) |
| Background    | base00 (terminal 0)  | Base03 (terminal 8)  |
| Bold          | base06 (terminal 13) | Base1  (terminal 14) |
| Links         | base0D (terminal 4)  | Blue   (terminal 4)  |
| Selection     | base02 (terminal 11) | Base0  (terminal 12) |
| Selected Text | base05 (terminal 7)  | Base03 (terminal 8)  |
| Cursor        | base05 (terminal 7)  | Base0  (terminal 12) |
| Cursor Text   | base01 (terminal 10) | Base03 (terminal 8)  |

