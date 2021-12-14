# Land Sample

> Learn the basic setup and workflow for tiled level from demo asset pack.  

----


[![Cover](../_media/LandTutorVideoCover.png)](https://youtu.be/nKz3ar4LS-8)

---

(below are text content in this tutorial video)


### Set up tiled level item

First, Checkout you installed the plugin. 

In Content Browser, Create a new tiled item set.

Show plugin content to find my demo contents. 

The pack is designed with size 100 x 100 x 100, no need to change any setup here.

Drag all meshes in *DemoLand/Meshes* (exclude *SM_PowerCoin*) to palette.

No need to change any value, just click confirm.

Drag *BP_Coin* from *DemoLand/BP* to palette.

Select *SM_DiagSide*, *SM_DiaSideBottom*, two flowers, grass, mushroom, and *BP_Coin*.

Set their **structure** type as **prop**.

Make sure each mesh is inside the grid.

Change the anchor position to **corner** for all box-like mesh.

The others should just remain **bottom**.

If all is well, save this item set and close it.


### Editor Tutorial

Drag **Tiled item set** directly to map.

Click Edit in detail panel to start.

Change number of X, Y tiles to 15.


- Paint

Under **Paint** , select item in the palette.

Paint it with click or drag.

Select different items to play aropund.

Holding **Shift** to enter quick eraser.

It will only erase selected item.

Holding **Ctrl** to enter strait mode.

Will fix your brush vertical or horizontal.

(Paint a bunch of thing to demo)

- Eraser

Change to eraser mode.

Eraser will only ease targeted **placed type** and **items**.

You can also change the earser extent.

- Eyedropper

Change to eyedropper.

Hover to placement of interest and click it.

Will select it and switch to paint mode.

With short cut **X** to enter eyedropper, swiching item could be faster.

- Toggle Grid

Toggle helper grids.

- Select 

Change to select mode.

**Shift + Right Mouse Drag** to select placements to copy.
Paint them where you want with click.

Can also enter select mode directly in paint mode (**Shift + Right Mouse Drag**).

- Rotate / Mirror

With item selected in paint mode, you can:

Roate item with **Q** and **R**.

Mirror item with **1**, **2**, and **3**.

- Raise / lower floor

Add more floors.

Press C and Z to quick raise or lower floor.

Structure items are not allowed to overlap.

- Explain placement Rule 1

We've set some items as **prop**.
They are differed in overlapping behavior.

**Props** are allowed to overlay each other.

**Structures** are only allowed to exist one per tile.
When new one is painted, it will replace previous one.

- Multimode

You can enable multi-mode to break the rule.

Take care it will introduce unwanted overlapping.

- Quit

Press **Esc** to exit.

### Timelapse demo

Now, I'll paint a simple level from begining.

Take me about 10 minutes to finish. 

Pretty neat?

- Promoto Asset

You can promote it to reusable asset.

Drag **tiled level asset** to map.

Edit anything in asset editor will reflect on all tiled level on map.

- Ending

That's it.

A simple tutorial and demo for what tiled level is capable of.
Hope you it.

