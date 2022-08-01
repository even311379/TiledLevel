# Tiled level in Gametime - API
## Remove Item Line Trace Single

Use single line trace to detect and remove the first hit tiled item. Just a wrapper of **SingleLineTraceByChannel** and **RemoveItem_FromHit**.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/RemoveItem_LineTraceSingle.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Trace Start | Vector     | Start point of the line trace. |
| Trace End   | Vector     | End point of the line trace. |
| Show Debug  | Boolean    | Should show debug hint? |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  Is an item placement removed? |
