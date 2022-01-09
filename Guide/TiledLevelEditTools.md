# Tiled Level Edit Tools

Tiled level plugin provide these tools to edit the placement of your items. Should make this process way easier.

## Tiled Level Editor Layout
![Tiled Level EdMode](../_media/EditTools.png )

## 1. Setup

"Reset tile size" so that to set different tile size, and the hit "Confirm".
All painting process will be blocked if tile size not confirmed.  
Set the number of tiles in X and Y axis. You are not allowed to paint outside this area.  

## 2. Floor Tool

A layer system implemented in 3D world. Paint items on active floor.

#### Tiled Floor List
Select floor to edit, you can also **hide / unhide** floor. Right click on any floor will open advaced action menu.

#### ![icon](../_media/icons/AddNewFloorAbove_128x.png ':size=32 :no-zoom' ) ![icon](../_media/icons/AddNewFloorBelow_128x.png ':size=32 :no-zoom' )Add New Floor Above / Below
Create new empty floor above / below, the position of the rest floors will change accordingly.

#### ![icon](../_media/icons/MoveFloorUp_128x.png ':size=32 :no-zoom' ) ![icon](../_media/icons/MoveFloorDown_128x.png ':size=32 :no-zoom' ) Move Floor Up / Down
Move selected floor up / down, along with all placements within.

#### ![icon](../_media/icons/MoveAllFloorsUp_128x.png ':size=32 :no-zoom' ) ![icon](../_media/icons/MoveAllFloorsDown_128x.png ':size=32 :no-zoom' )Move All Floors Up / Down
Move all floors up / down.

#### ![icon](../_media/icons/DuplicateFloor_128x.png ':size=32 :no-zoom' )Duplicate Floor 
Duplicate selected floor above, along with all placements.

#### ![icon](../_media/icons/DeleteFloor_128x.png ':size=32 :no-zoom' )Delete Floor 
Delete selected and all its placment.


![Floor System](../_media/DemoGIF/FloorSystem.gif)


## 3. Edit Tools

### Edit modes
#### ![icon](../_media/icons/SelectTool_128x.png ':size=32 :no-zoom' )Select (G)
**Shift + right mouse drag** to select placements in "active floor" inside the box selection area. With placements selected, you can paste them where you want with **left mouse click** or **shift + right mouse drag** again to select different area. You can switch to select mode in paint mode with **shift + right mouse drag**. 

#### ![icon](../_media/icons/PaintTool_128x.png ':size=32 :no-zoom' )Paint (B)
Paint select item to active floor with left mouse click.  
You can also drag paint by holding left mouse buton.

**Strait**: While holding **Ctrl** during drag paint, it will force the brush move only hertical or horizontal manner.  
**Quick Eraser**: Holding **Shift** will enter quick eraser mode, it will only easer selected item, which are most likely the ones you just paint. 


#### ![icon](../_media/icons/EraserTool_128x.png ':size=32 :no-zoom' )Eraser (E)
Select which placed type to ease.  
Set the easer extent.  
Set whether allowed to erase for each individual item.  


#### ![icon](../_media/icons/Eyedropper_128x.png ':size=32 :no-zoom' )Eyedropper (X)
Make you easier to swich between item to paint. Hover the placement you've painted, and left mouse click to select it to paint.

---

#### ![icon](../_media/icons/Step_128x.png ':size=32 :no-zoom' )Step Control
Options to control step size and origin of grid movement when painting. 

> When most of your items are of extent 2x2, you may want to set step size as 2, and set back to step size as 1 only when you need to paint some items with extent 1x1.  

#### ![icon](../_media/icons/ToggleGrid_128x.png ':size=32 :no-zoom' )Grid (Tab)
Toggle the visibility of bounding area box and floor grid.

---

#### ![icon](../_media/icons/RotateCCW_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/RotateCW_128x.png ':size=32 :no-zoom' ) Rotate (Q/R)
Rotate item 90&deg; in paint mode. (Q: Counter-clock wise / R: Clock wise)

#### ![icon](../_media/icons/MirrorX_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/MirrorY_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/MirrorZ_128x.png ':size=32 :no-zoom' ) Mirror (1/2/3)
Mirror item in paint mode (1: X / 2: Y / 3: Z axis)
> Mirrored item is less performance-efficient. Since the "Hierarchical Instanced Static Mesh Component" does not support negative scale, I could only implement this funtion by spawning static mesh actors instead.

#### ![icon](../_media/icons/EditLower_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/EditUpper_128x.png ':size=32 :no-zoom' ) Edit Upper / Lower (Z/C)
Move to upper/Lower floor if exist.

[![Cover](../_media/LandTutorVideoCover.png)](https://youtu.be/nKz3ar4LS-8?t=154)


#### ![icon](../_media/icons/Multi_128x.png ':size=32 :no-zoom' ) Multi Mode (M)
Allows you to bypass all placement rules. Just place the item to that position without any replacement operation.

#### ![icon](../_media/icons/Snap_128x.png ':size=32 :no-zoom' ) Auto Snap (N)
You can toggle this button to enable/disable snap mode (only when the item is set to snap to floor or wall). 

Snap to floor

![DEMO](../_media/DemoGIF/SnapFloor.gif)

Snap to wall

![DEMO](../_media/DemoGIF/SnapWall.gif)



## 4. Item Set Palette

- You can change different item set as long as the tile size is the same.

- Some tranformation settings of selected item are allowed to set here. Changing settings won't affect those already painted.


## 5. Preview Viewport

This is where you paint items.

---

