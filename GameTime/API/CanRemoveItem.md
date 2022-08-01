# Tiled level in Gametime - API
## Can Remove Item

**OVERRIDABLE FUNCTION**

Final check for if you are allowed to remove particular item. Overrride it to meet your need.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/CanRemoveItem_01.png" alt="drawing" width="50%"/>
<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/CanRemoveItem_02.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Item to Remove| Tiled Item Object Reference | The item that is about to remove. |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  Can remove this item? |
