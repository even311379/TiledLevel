# Placement Rule


> What should happen when you paint a new item to where there is already occupied? What should this new item do? Replace or overlay?
> 
> Painting a "Wall with DoorFrame" on a "normal wall", you want to just replace it.  
> Painting a "Door" on "Wall with DoorFrame", you want to overlay it.

Following the 3 rules stated below to properly set up each tiled item, you can fully control this behavior.

## 1. One Tile One Structure

There is always one struture per tile. When paint a new structure item on it, the previous one will be replaced.
When it is a **Prop** type item, it will overlay.
You must set [**Structure Type**]() properly for each tiled item.


Paint Two structure item

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

Paint prop item on structure item

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)


## 2. Zero Same Item Overlay
No overlay between same item. When paint a same item which is ovelapping with existing item, the previous will be replaced.

Paint same item on structure item (Floor with size 2X2)

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)


## 3. Separated Placement Space
Different [**placed type**](Glossary?id=placed-type** will never interfere each other. The above 2 rules only work on same placed type.

Paint **Block Type** item on **Floor Type** item.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

---

## Bypass Rules
These rules above are make painting item in most intuitive manner. However, sometimes these rules are hindrence to your work flow. You can turn on [**Multi Mode**](Guide/TiledLevelEditTools?id=-multi-mode-m) to bypass the rules. 


Paint rotated **block-struture** item at same tile.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

--

## when trying to record, edit video, and converting to GIF. Spotting there is minor UI display issue... But I am heavily modifying source code now... Need to wait...

