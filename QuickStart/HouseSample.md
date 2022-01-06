# House Sample

> Learn the how to setup asset pack with all placed type.  

--- 

[![Cover](../_media/HouseTutorVideoCover.png)](https://youtu.be/ai1kIieHu6o)

---
### (The text content in this video) 

Hope you like!

For intuitively assembling buildings, Tiled Level extends the idea of blocks to different placed types. 

Including **Block**, **Floor**, **Wall**, **Edge**, **Pillar**, and **Point**. 

This tutorial will use the **House Sample pack** to show you how to properly set up a **Tiled Item Set** consisting of different placed types. 

Create a new **Tiled Item Set** and open it to edit. 

Navigate to *TiledLevelContent/DemoHouse/Meshes*.

Adding new items without proper setup will result in unnecessary one-by-one tuning. 

Set tile size to **250 x 250 x 250** and include all placed types.

This will make the extent and placed type prediction accurate as possible for new mesh-based items. 

Now, drag all meshes except *SM_Door* to palette.

The tile extent and placed type are set with some value close to correct. 

You can tune them afterward. 

Navigate to *TiledLevelContent/DemoHouse/Blueprints*, drag *BP_Door* and *BP_Goal* to palette. 

The extent and placed type prediction is not supported on blueprints, you need to manually tune them. 

You can drag and blueprint, no need to inherit any class or add some interface. 

For example, let's just drag intact *ThirdPersonCharacter* to the palette. 

Let's check and modify the setting for each item. 

*SM_RoodTip* should be **Point**. 

*BP_Door* should be **Wall** and **Prop**.

*SM_Glass* should be **Prop**. 

*SM_RoofTileSide* should be **Prop**. 

*SM_RoofTileTop* should be **Edge**. 

Set pivot point of *ThirdPersonCharacter* to the **center**. 

*SM_RoofTileOuterCornerTip* is wrongly designed for the purpose of the demo. 

Turn on **Auto-Placement**. 

Select *SM_RoofTileOutterCorner* and fix it to top-left as reference. 

Now, set the location under *TransformAdjustment* to **(25, 15, 0)**. 

Final check, save and close. 

Select the item set just created, right-click to **create tiled level**. 

Start to edit. 

Different placed type items will never interfere with each other. 

The rest tools are all the same, check my previous video. 

Now you can just paint what you like. 

Here is a timelapse demo.

That's it!

Hope you enjoy this plugin.