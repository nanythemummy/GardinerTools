
GardinerTools
 
Tools for Working with Ancient Egyptian Texts and Transliterations

GardinerTool.py

Purpose

To help with the process of converting ascii representations of glyphs and transliterations into Unicode.

Requirements

cltk (Classical Languages Toolkit)
The requirements and unicode fonts mentioned above.
Usage

There are two scripts: get-glyph and get-translit One converts a gardiner signlist code into a unicode glyph, the other converst an ASCII Manuel de Codage string into transliteration characters in unicode.

get-glyph

python GardinerTool.py get-glyph B1
result is [unicode hieroglyph not supported in readme apparently]
get-translit

python GardinerTool.py get-translit "Ink sAH=k"
Result is [unicode translit characters not supported in readme apparently]