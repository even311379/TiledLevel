# Asset Pack Tips

> Tips for easier integrate with modular asset packs

- Use "Fantacy Kingdom" asset pack from Synty Studios as example

## 1. Choose a feasible tile size

When using a third-party pack, the first step is to find out a feasible tile size value. Open its demonstration map, and check out the size of major structure meshes. In this sample, the basic unit is designed in 250 x 250 x 250, however, it also contains half-sized units. You can consider set tile size as half and set step size as 2.

TODO: Add lots of reference image?



## 2. Choose assets to use

There could be hundreds of meshes from your asset pack, making it so difficult to choose what to use. The recommended workflow is to open its demo map and direct grab these meshes to the tiled item set. Enabling "actor palette" plugin will make this process much easier. You can just drag the meshes you like on demo map to your tiled item set.

## 3. Adjust item origin

Most origin issues should be fixed with a proper anchor point, however, in case it's not fixed, manually adjust translation with a **multiplier of tile size**. Do not set translation adjustment with weird values. There exist solid reasons for the assets are set with these origins. Once you just set it randomly, the asset could not perfectly align with others.

## 4. Duplicate asset if necessary

When one modular asset is used with a few different scales repeated during assembling, duplicating that asset with different scales and then treat them as different tiled items would be better.  
