# Tiled Level Edit Tools

Tiled level plugin provide these tools to edit the placement of your items. Should make this process way easier.

## Tiled Level Editor Layout
![Tiled Level EdMode](../_media/TiledLevelEditor_sample.png )

## 1. Setup

Confirm / Reset tile size

## 2. Floor Tool

Floor deside Z position of each placement.

#### Tiled Floor List
Select floor to edit, you can also **hide / unhide** floor. Right click on any floor will open advaced action menu. The one I used most often is **clear all instance in this floor**.

#### ![icon](../_media/icons/AddNewFloorAbove_128x.png ':size=32 :no-zoom' ) ![icon](../_media/icons/AddNewFloorBelow_128x.png ':size=32 :no-zoom' )Add New Floor Above / Below
Create new empty floor above / below, the position of rest floors will change accordingly.


#### ![icon](../_media/icons/MoveFloorUp_128x.png ':size=32 :no-zoom' ) ![icon](../_media/icons/MoveFloorDown_128x.png ':size=32 :no-zoom' ) Move Floor Up / Down
Move selected floor up / down, along with all placements within.

#### ![icon](../_media/icons/MoveAllFloorsUp_128x.png ':size=32 :no-zoom' ) ![icon](../_media/icons/MoveAllFloorsDown_128x.png ':size=32 :no-zoom' )Move All Floors Up / Down
Move all floors up / down.

#### ![icon](../_media/icons/DuplicateFloor_128x.png ':size=32 :no-zoom' )Duplicate Floor 
Duplicate selected floor above, along with all placements. Can save lots of time for you.

#### ![icon](../_media/icons/DeleteFloor_128x.png ':size=32 :no-zoom' )Delete Floor 
Delete selected and all its placment.


## 3. Edit Tools

#### ![icon](../_media/icons/SelectTool_128x.png ':size=32 :no-zoom' )Select (Shift + Right Mouse Drag)
#### ![icon](../_media/icons/PaintTool_128x.png ':size=32 :no-zoom' )Paint (B)
#### ![icon](../_media/icons/EraserTool_128x.png ':size=32 :no-zoom' )Eraser (E)
#### ![icon](../_media/icons/Eyedropper_128x.png ':size=32 :no-zoom' )Eyedropper (X)

---

#### ![icon](../_media/icons/ToggleGrid_128x.png ':size=32 :no-zoom' )Grid (Tab)
Toggle the visibility of bounding area box and floor grid.

---


#### ![icon](../_media/icons/RotateCCW_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/RotateCW_128x.png ':size=32 :no-zoom' ) Rotate (Q/R)
Rotate item 90&deg; in paint mode. (Q: Counter-clock wise / R: Clock wise)

#### ![icon](../_media/icons/MirrorX_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/MirrorY_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/MirrorZ_128x.png ':size=32 :no-zoom' ) Mirror (1/2/3)
Mirror item in paint mode (1: X / 2: Y / 3: Z axis)
> Mirrored item is less performance-efficient. Since the "Hierarchical Instanced Static Mesh Component" does not support negative scale, I could only implement this funtion by spawning static mesh actors.

#### ![icon](../_media/icons/EditLower_128x.png ':size=32 :no-zoom' )![icon](../_media/icons/EditUpper_128x.png ':size=32 :no-zoom' ) Edit Upper / Lower (Z/C)
Move to upper/Lower floor if exist.

#### ![icon](../_media/icons/Multi_128x.png ':size=32 :no-zoom' ) Multi Mode (M)
Allows you to bypass all placement rule. Just place the item to that position without any operation.

#### ![icon](../_media/icons/Snap_128x.png ':size=32 :no-zoom' ) Auto Snap (N)
When Item is set snap to floor / wall, toggle this button to enable / disable snap mode.

## 4. Active Item Set Options
Change Active Item Set?


## 5. Item Set Palette


## 6. Item Detail


## 7. Preview Viewport

This is where you paint items.


---

## Edit for Instance Layout

Setup and 

