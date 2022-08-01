# Tiled level in Gametime - API
## Activate Eraser Mode

Activate the eraser in gametime. You can not specified which items are excluded in eraser.

> (V2.0.1) The CanRemoveItem has no effect on eraser now. This will be fixed in next update!

<img src="https://raw.githubusercontent.com/even311379/TiledLevel/main/_media/GametimeAPI/ActivateEraserMode.png" alt="drawing" width="50%"/>

### > Input
|             |         |       |
| :---        | :----   | : --- |
| Any Type    | Boolean | Should apply on all placed type?  |
| Target Type | EPlacedType Enum | Which placed type to erase?  |
| Eraser Size | Int Vector structure | The extent of the eraser. |

### > Output
