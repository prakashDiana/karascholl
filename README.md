# Kara Std Font(s)


A standard font.

It has PostScript glyph names.

**GID** | **Name**
--- | ---
0 | .notdef
1 | NULL
2 | CR
3 | space

And more.

It says, “TrueType outline fonts should have the following four glyphs at the glyph ID indicated. These were listed in Apple’s original TrueType specification. These glyphs are recommended to allow for the same version of the font to work on both Windows and Macintosh.”

It also said that the .notdef glyph is very important for providing the user feedback that a glyph is not found in the font. This glyph should not be left without an outline as the user will only see what looks like a space if a glyph is missing and not be aware of the active font’s limitation.

For 16.

Apple Glyph Names
Glyph ID | Name
--- | ---
0	| .notdef
1	| **.null**
2	| **nonmarkingreturn**
3	| space
4	| exclam
5	| quotedbl
6	| numbersign
7	| dollar
8 | percent
9	| ampersand
10 | quotesingle

and more.

TrueType outlines say that: 
&#x2022; Glyph 1 should have no contours and zero advance width.
&#x2022; Character U+000D (carriage return) should map to a glyph with a positive advance width.
&#x2022; Characters U+0001-001F (misc ASCII control codes) and U+007F (delete) should be mapped to glyph 0 (with some exceptions noted below).
&#x2022; Characters U+0000 (null), U+0008 (backspace) and U+001D (group separator) should map to glyph 1.
&#x2022; Characters U+0009 (horizontal tabulation), U+0020 (space) and U+00A0 (no-break space) should map to a glyph with no contours and a positive advance width.
&#x2022; Characters U+0009 and U+0020 should map to a glyph with the same width.
