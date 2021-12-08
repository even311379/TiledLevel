
# Setup Item Set

Item Set is a place where you register mesh or actor to tiled item, defines your rule to paint each item. 

An item set can be used in multiple tiled level as long as the tile size is the same.

<!-- A image with hint to explain each stuff -->

![Tiled Item Set Editor](../_media/ItemSetEditor_temp.png ':size=800')
## 1. Item Set Detail

### Tile Size

### New Item Settings

These value will affect **prediction** for the placed type and extent of new items, save you time to change them latter. Since you may add hundreds of new item at same time, these will save you bunch of time.


## 2. Tiled Item Palette

### Search and View Option

Filter registered items.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

### Registered items / Drop region

Drag mesh / actor from content browser to here will register new items to this item set. 

Select item here to preview how this item placed inside the tiled brush based on its current setting.  

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

### Item Detail

Modify the detail of selected item. 

#### Mesh / Actor

The source mesh / actor of this item.

#### Tiled Item

These will make a lot impact on painting, not allowed to change except here.  
[**Extent**](/Glossary?id=tile-extent)  
[**Placed Type**](Glossary?id=placed-type)  
[**Structure Type**](Glossary?id=structure-type)  

Make sure you understand the meaning of them. Checkout [Placement Rule](/Guide/PlacementRule) and [Glossary](/Glossary). 

#### Auto Placement
Only available in mesh item.  
Due to the pivot point of each mesh could differ, this will adjust pivot center to geometry center from source mesh.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

> You may not want to turn on when the pivot point of source mesh is carefully designed for specific ends. 

#### Anchor Position

The anchor position of item inside the tile. Different placed type would differ in anchor position options.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

**Fit** option only appear when auto placement is turn on. It will adjust the traslation and scale to fit the actual tile size. You can also override **wall thickness** or **floor height** here.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)


#### Transform Adjustment

If transformation adjustment from auto placement and anchor position does not still position you item in a perfect way, this is the place for final adjustment.


## 3. Editor Toolbar
#### ![icon](../_media/icons/FixItem_128x.png ':size=32 :no-zoom' ) Fix Item

Fix current seleted preview item in preview viewport at given positions around the next selected preview item. May help you setup item properly.

#### ![icon](../_media/icons/UpdateLevels_128x.png ':size=32 :no-zoom') Clear Fixed:

Rmove all preview items fixed in viewport.

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

## 4. Preview Scene Viewport

Preview seleted item for how this 

## 5. Preview Scene Setting

Adjust preview scene.
