# Patch Note
---

### Upcoming 

- Fullfill 100% functionality for autopaint:
  - Random seed
  - Add support for other placed type
  - Add support for fill tool and eyedropper
  - game time support with auto paint

- rewrite selection tool
- add vertical edit mode



---
### v3.0.0 (2023.7.28)
Add auto paint support
- New asset type (auto paint rule) and its specific editor
- New paint mode to apply auto paint
(in total, )


### v2.2.0 (2023.2.22)
- Improved better undo-redo steps during painting
- Improved asset preview thumbnail
- Improved: show approximate size of mesh in tiled item set editor
- Fixed AI navigation issues perfectly (both in editor and gametime)
- Fixed selection tool crashes 


### V2.1.2 (2022.10.16)
- Fix crash issue when source mesh/blueprint of tiled item was deleted.


### V2.1.1 (2022.10.08)
- Fix additional position offset when initialize tiled level gametime with existing levels included.
- Fix AI navigation geometry disappeared after edit tiled levels on maps. (This issue still occurs on gametime support...)
- New: Add right click action **merge and replace here**, which will replace previous tiled level with a revertible static mesh actor.


### V2.1.0 (2022.8.28)
- New feature: Add **template item**, now you can use existing tiled level asset as template during editing.
- New: Add preview thumbnail for tiled level asset
- New: Add target item picker for **Restriction item**
- New: Selection mode supported multiple floors now.
- Modify: Improve the assessment of selection range for **selection mode** 


### V2.0.2 (2022.8.11)
- Fix crashes when calling **InitializeGametimeSystemFromData** while preview item is active.
- Fix preview item material display error. Sometimes, it displayed "Can Not Build" while it is not the case.
- Fix wrong preview location. After rotation and change preview item, the position may go wrong.
- Modify: Remove inner faces for restriction item.
- Modify: New material for restriction item that you can show only edges of each box now.

### V2.0.1 (2022.7.29)
- fix packaging error

### v2.0.0 (2022.7.23)
**New features (game time support)**
- TiledLevelGametimeSystem
- Bind TiledItemSet with any customizable data table
- Add special tiled item (restriction item) for game time needs
<br>[**Quick Start here**](GameTime/QuickStart)


**Issues and bugs fixed**
- Fix crash in fill tool when the number of tiles in X and Y axis is not equal.
- Fix crash after the source asset (blueprint or static mesh) used for tiled item is forced removed.
- Fix can not change tile size! (An error introduced in last update.)
- Fix temporally freeze PIE when start whenever instanced tiled level is on map.
- Modify: Block adding "controller" or "game mode" as tiled item. (Previously, all actors are allowed to do so, which is not reasonable enough.)
- Modify: Reduce source code duplication.
- Modify: Remove warning message: can not find xxx files.




### v1.5 (2022.5.12)
- Add new feature: [**Merge**](Guide/WorkFlow?id=merge-tiled-level) (convert tiled asset to static mesh)
- Remove reset tile size for instanced tiled level actor on map.

### v1.4.1 (2022.4.19)
- fix wrong z position for preview edges in fill mode
- fix potential crashes if fill across hidden floors
- fix potential crashes if erase across hidden floors
- update all tool behavior in hidden floors
- add hide /unhide all floors option in context menu in floor list widget

### v1.4 (2022.4.12)
- Add new [**fill tool**](Guide/TiledLevelEditTools?id=fill)
- fix selection extent
- UE5.0 release

### V1.3 (2022.3.18)

- Reimplement Selection mode. You can rotate selected tiled item instances.
- Fix eyedropper bugs...
- Add Linux support

### V1.2 (2022.1.23)

- Add material override for mesh-based item
- Fix Bug: When activating some other plugins will make ue4 fail to load this plugin.
- Fix Bug: Deleting item set will crash editor sometimes.
- Fix Bug: Breaking tiled level will result in wrong transformation if that tiled level is rotated or scaled.
- Fix Bug: Duplicate tiled level on map will not spawn its attached blueprints until reload the map.
- Fix Bug: Rotation of paint brush will reset when mouse leave the level viewport.

### V1.1 (2022.1.10)

- [**Step Size Control**](Guide/TiledLevelEditTools?id=step-control)
- Add some missing tool tips.
- UE5.0 is supported.

  > So far, I can only provide the source code of this version. If you need it now, send me a screenshot of the purchase receipt (or any other proof), and I'll give you a download link to this version.

### V1.0 (2021.12.16)

- First Release  Happy Happy

