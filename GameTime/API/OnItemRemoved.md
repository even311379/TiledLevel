# Tiled level in Gametime - API
## On Item Removed

**EVENT DISPATCHER**

Triggered after item is removed. You can bind custom events anywhere, ex: spawn pickup actor, spawn particle, or play sound. 

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/OnItemRemoved.png" alt="drawing" width="50%"/>


### > Inputs for binding 
|             |         |       |
| :---        | :----   | : --- |
|  | Tiled Item Object Reference | The item that is just removed. |
|  | Vector | The world position where the item is removed |
