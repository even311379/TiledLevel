# House Sample

---
Make sure tiled level is installed to your engine version. It currently supportes 4.26 and 4.27.

All assets are included in y sample project [TiledLevelDemo](https://drive.google.com/file/d/1AuOV13Gk-h3n75sz71dKByfkAiL1vTQ2/view?usp=sharing). 

---

Unlike the block demo, the majority of retangle shaped buildings are composed of these structures:  floor, wall, pillar, and beam. I'll show you what they are.

You need "Tiled Item Set" to setup all the modular assets you want to use.
After "Tiled Item Set" is well prepared, you can just drag it to level or create a reusable asset: "Tiled Level Asset" to paint.



### Setup Item Set

Create a new item set
Right click on content browser, under tiled level category, select Tiled Item Set.

Open the new asset
Set the [**Tile Size**](/Glossary?id=Tile_Size) as 250 x 250 x250. 

> **Tile Size** is very IMPORTANT across all the edit process, may differ based on your asset packs.

Check use all placed type, these are just for make setup quicker. You can always change them afterward.
The prediction threshold is used to adject the auto extent prediction based on your raw mesh bound size.


Drag all meshes in the palette, an additional dialog will pop up and you can quick adject these variables.
Drag BP Door to pallete, set it as wall prop.

Make sure all structure type is set as structure, and set window, door BP as prop.


Tile Exent


### Create Tiled Level
1. Drag your item set directly to level. Click edit to start.
2. Right click on Item Set and choose create a asset from it, open this new asset.


### Edit Tiled Level

Viewport navigation is as the default way. 

Choose paint mode.
Select item "Floor" to paint and square area.
> You can left click to paint one tile or left drag to paint around. 

> Holding **Shift** during paint mode will become quick eraser mode. You can quickly erase the current selected item, while leave others intact.

> Holding **Ctrl** during paint will become stait mode, force your restraint your stroke to only vertical or horizontal direction.

Select "Wall" to paint around floor. Press **Q** or **R** to rotate.

Select "DoorFrame" to paint on one of the wall. Since in 


### Drag to you map