# PuzzleBlocs
3D Printable 25mm blocks for real life Minetest/Minecraft.  WIP


## Printing

The whole base set should print without any support.

## Naming Convention

Blocks are named starting with the width, depth, and height in 25mm, 25mm, and 8.33mm units respectively, followed by one letter for every
side missing a connector.  A 225FLRoundBin is inteded to go on the front right corner of a layout, and so has no connectors on the front or right.

If there is no missing connectors, use M for Middle.   This way every block name identifies where it can go.

## Assembly

The male connector holds down the female end, so you must assemble starting from the rear right, slotting the male end into the female rail.

Layers have no vertical stacking features.  They are joined purely by using tall blocks that span multiple layers.

A 113 block is a perfect 24mm cube,  but heights vary by 8.33mm units, so unlike real Minecraft style blocks you don't use evenly sized layers.

## Gridfinity

There is a gridfinity holder block you can use, it is a 221M size.  However, gridfinity tiles are 42mm and we are 50mm for a 221, so there is wasted space
on all sides for the connector.


## Spec

(WIP!  See FreeCAD files!! They are made using Assembly3)

25 mm X and Y units, 8.33mm vertical.  Subtract 1mm from the real dimension for clearance, so a 2 unit wide block is really 49mm.

Centered on the back and right side is a male dovetail.  It is 5mm wide at the base and extends 4mm.  It's angle is 40 degrees per side.

The female dovetail is 4.5 deep, and 6.4mm at the base for clearence, and goes on the left and front.


At the bottom of the male, the first 0.5mm is missing, then there is a 45 degree cutout, because we have to print as an overhang.

At the bottom of the female, we have a 45 degree wedge stopper extending from the back to the front, going downwards as you go away from the center of a block.

Should a block be multiple units, you must have a dovetail every 25mm, and the first shall be 12.5mm from the center.

The male dovetail only extends 8.333mm starting from the base of the model.

