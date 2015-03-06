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


Prefix  |	Type
--------|-------
ic_		|	Icon
img_	|	Image
btn_	|	Button



## Sketch type styles naming convention

Sketch supports styles, but doesn't allow us to combine them, like CSS. That means we often have to create variants of the same style. Keep all variants consistent.

Use app hierarchy with colons (:) to name styles. Try to adhere to HTML styles. Example:

	Function:	Navigation
	Element:	H2
	Variant:	Centered

Name of style: `Nav:H2:Centered`

This will help when exporting CSS; simply replace the colons with the appropriate hierarchy.

## Sketch Artboard Naming Convention

`Section - Detail (user state - ticket state)`

As the app contains multiple possible **user states**, it's important to include them on the artboard name to avoid confusion. However, we should keep things as minimal as possible to keep it readable within the narrow layer area Sketch provides.

State					|	Short
--|--
Not signed in			|	NoSign
Signed in				|	Sign
Has ticket				|	Tkt

States can be combined using a dash.

**Example:** Home screen, no live concerts approaching; user is signed in, but has no ticket.




## Export settings

- normal (@1x, no suffix)
- @2x
- @3x (for iPhone 6 Plus)