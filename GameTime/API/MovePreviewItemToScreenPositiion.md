# Tiled level in Gametime - API
## Move Preview Item to Screen Position

Must activate preview item beforehand. Floor position is required. Convert the input screen postion to **tile position** and then try to move preivew item there. If the converted **tile position** is not inside the boundary or is still inside same tile position, it won't move.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/MovePreviewItemToScreenPosition.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Screen Position | Vector 2D structure | The position on current screen. (0, 0) is the top left corner.  |
| Floor Position| Integer | 0 means 1F, -1 means B1. |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  True if the preview item is actually moved. |
