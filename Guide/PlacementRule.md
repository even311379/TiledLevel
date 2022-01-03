# Placement Rule


> What should happen when you paint a new item to where it is already occupied? What should this new item do? Replace or overlay?
> 
> Painting a "Wall with DoorFrame" on a "normal wall", you want to just replace it.  
> Painting a "Door" on "Wall with DoorFrame", you want to overlay it.

Following the 3 rules stated below to properly set up each tiled item, you can fully control this behavior.

## 1. One Tile One Structure

A tile can only contain one **structure** item.  
When painting a new **structure** item on top of any existing **structure** item, the previous one will be replaced.  
When it is a **Prop** type item, it will overlay.  
You must set **Structure Type** properly for each tiled item.  


Paint Two structure item

![Alt Text](../_media/DemoGIF/PlacementRule1_Structure.gif)

Paint prop item on structure item

![Alt Text](../_media/DemoGIF/PlacementRule1_Prop.gif)

## 2. No Same Item Overlapping
No overlapping between the same item. When painting an item ovelapped with existing same item, the previous will be replaced.

Paint same item on structure item (Floor with size 2X2)

![Alt Text](../_media/DemoGIF/PlacementRule2.gif)


## 3. Separated Placement Space
Different **placed type** items will never interfere with each other. The above 2 rules only work on the same placed type.

Paint **Block Type** item on **Floor Type** item.

![Alt Text](../_media/DemoGIF/PlacementRule3.gif)

---

### Bypass Rules
These rules above aim to make painting items in the most intuitive manner. However, sometimes these rules are a hindrance to your workflow.  
You can turn on [**Multi Mode**](Guide/TiledLevelEditTools?id=-multi-mode-m) to bypass the rules.

