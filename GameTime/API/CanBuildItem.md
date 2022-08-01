# Tiled level in Gametime - API
## Can Build Item

**OVERRIDABLE FUNCTION**

Final check for if you are allowed to build particular item. Overrride it to meet your need.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/CanBuildItem_01.png" alt="drawing" width="50%"/>
<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/CanBuildItem_02.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Item to Build| Tiled Item Object Reference | The item that is about to build. |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  Can build this item? |
