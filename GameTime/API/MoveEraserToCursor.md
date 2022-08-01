# Tiled level in Gametime - API
## Move Eraser to Cursor

Let the eraser follow your cursor. Must activate eraser beforehand. Convert the cursor position to **tile position** and then try to move eraser there. If the converted **tile position** is not inside the boundary or still inside same tile position, it won't move.

> (V2.0.1) Will add new parameter to specify the player index in next update. Now, it will move to cursor position from the first player.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/MoveEraserToCursor.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Floor Position| Integer | 0 means 1F, -1 means B1. |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  True if the eraser is actually moved. |