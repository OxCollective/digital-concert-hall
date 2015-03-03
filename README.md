### Digital Concert Hall
# Design guidelines

## Technical info

- The file is created at @1x
- No iOS **Status Bar** is necessary (it's added by Marvel App)
- Marvel App address:


## Sketch layer naming convention

Layers that need to be exported should be named according to this convention.


Prefix  | Type
--------|-------
ic_		| Icon
img_	| Image


## Sketch type styles naming convention

Use app hierarchy with colons (:) to name styles. Try to adhere to HTML styles. Example:

	Page:		Home
	Artboard:	Home (iPhone)
	Element:	H2

Name of style: `Home:Home (iPhone):H2`

This will help when exporting CSS; simply replace the colons with the appropriate hierarchy.


## Export settings

- normal (@1x, no suffix)
- @2x
- @3x (for iPhone 6 Plus)
