### Digital Concert Hall
# Design guidelines

## Technical info

- The file is created at @1x
- No iOS **Status Bar** is necessary (it's added by Marvel App)
- Marvel App address:


## Sketch layer naming convention

1. Keep layer names concise and descriptive.  
2. Use dashes **-** instead of spaces
3. Use lowercase for layers that will be exported

Layers that need to be exported should be named according to the following convention:


Prefix  | Type
--------|-------
ic_		| Icon
img_	| Image


## Sketch type styles naming convention

Sketch supports styles, but doesn't allow us to combine them, like CSS. That means we often have to create variants of the same style. Keep all variants consistent.

Use app hierarchy with colons (:) to name styles. Try to adhere to HTML styles. Example:

	Function:	Navigation
	Element:	H2
	Variant:	Centered

Name of style: `Nav:H2:Centered`

This will help when exporting CSS; simply replace the colons with the appropriate hierarchy.


## Export settings

- normal (@1x, no suffix)
- @2x
- @3x (for iPhone 6 Plus)
