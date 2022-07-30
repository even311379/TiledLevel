# Tiled level in Gametime - Custom data binding

To support custom data binding, all you need to do is to create your data table with a **KEY** variable that can link to the tiled items inside youe **tiled item set**. This plugin provides an automatic approach to help you make such linkage. The **GUID** in each tiled item will become the **RowName** in your data table.

1. Make linkage
Set the data table and click **testest**

New empty rows will populate with rowname the same as guid, while existing rows will stay unchanged.

If you add new item to item set after setup this linkage, just click "" and the new row will generate in your data table.



2. Edit right inside **tiled item set**
As the linkage is setup properly, you can edit the data just below the detail panel for each item. 

Much intuitive to come up with descriptions for these items, right?


3. Query it for what you want.
Now you can easily query the data for your needs. EX: