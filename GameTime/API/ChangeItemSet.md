# Tiled level in Gametime - API
## Change Item Set

Change the active item set.

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/ChangeItemSet.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| New Item Set| Tiled Item Set Object Reference | Must have same tile size, otherwise, change will fail. |

### > Output

|               |         |       |
| :---          | :----   | : --- |
| Return Value  | Boolean |  Is item set changed? |
