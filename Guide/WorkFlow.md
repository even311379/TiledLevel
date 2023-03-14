# Workflow

Here are some additional workflows that can help your level design in this plugin.

### Use Template item (v2.1)

You can reuse existing tiled level asset to new tiled level asset. Assuming you want to reuse a house in this manner, here's the steps to achieve it:

1. Create a tiled level that you want to reuse.
2. Create a spceial item inside the tiled item set, and set the template.
3. Paint it where you want.

[youtube video](https://www.youtube.com/embed/X41oPId1LCo ':include :type=iframe width=560px height=315px')



### Break Tiled level

You can always return normal level design workflow after using this plugin. By breaking tiled level, it is converted to separated static mesh actors or BP actors which allows you to fine tuning their properties. They are organized in each floor folders, which enable you to hide specific floors.


![Demo](../_media/DemoGIF/Break.gif)

### Merge Tiled level

You can convert tiled level asset to static mesh now!
There are three places where you can execute this command:
1. Right click on the tiled level actor on your map.
2. Right click on the tiled level asset on content browser.
3. Click the new toolbar button on tiled level editor.

> LOD and simple collisions will be setup automatically. No worries. <br/>
> All static mesh components in actor-based tiled item placed in your tiled level asset will also be merged to single static mesh.
So far, it doesn't support conversion from instanced static mesh components or procedural mesh components in your actor-baseed tiled item.

![Demo](../_media/DemoGIF/Merge.gif)


### Merge and Replace (v2.1)

You can merge your tiled level actor in your map to a special "revertible" static mesh actor. 

Right click on your tiled level actor and choose "merge and replace". A dialog will pop up to ask for a new file name for the merged static mesh asset. Then, a "revertible" actor will replace the original tiled level actor. You can revert it to tiled level actor for editing if you want.