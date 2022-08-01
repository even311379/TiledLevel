# Tiled level in Gametime - API
## Move Preview Item to World Position

Must activate preview item beforehand. Convert the input world locaiotn to **tile position** and then try to move preivew item there. If the converted **tile position** is not inside the boundary or is still inside same tile position, it won't move.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/MovePreviewItemToWorldPosition.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Target Location | Vector | World position to convert to tile position. |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  True if the preview item is actually moved. |
