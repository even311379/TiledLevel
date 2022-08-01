# Tiled level in Gametime - API
## On Item Fail to Remove

**EVENT DISPATCHER**

Triggered after failure to remove item. You can bind custom events anywhere, ex: spawn particle, or play sound. 

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/OnItemFailToRemove.png" alt="drawing" width="50%"/>


### > Inputs for binding 
|             |         |       |
| :---        | :----   | : --- |
|  | Tiled Item Object Reference | The item that is just failed to remove. |
|  | Vector | The world position where the item is about to remove but fail. |
