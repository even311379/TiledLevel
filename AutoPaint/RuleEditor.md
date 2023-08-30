# Auto Paint Rule Editor

Create auto paint item, define rules, and quick preview how they works.

## Editor overview

![Auto paint editor overview](../_media/AutoPaint/auto_paint_editor_overview.png)

## 1. toolbar
#### Add Item
Create new *auto paint item* to setup adjacency rules and use it as brush to paint. **Empty** item is registered automatically to represent as nothing on that position when setu[ adjacency rule.

#### Add Group
Create new *auto paint rule group* to to organise rules.

#### Edit/Delte/Duplicate/Copy/Paste
Common operations to edit *auto paint item* and *auto paint rule*. It will apply on selected one.

#### Respawn auto paint instances (Alt+R)
Update auto paint result with your lastest rules. All instances should be sync to lastest rules by default. However, in cases it doesn't, you can just press this button to sync. Besides that, due the the randomnes spawn based on your rule, you may want to trigger it to check different results.

## 2. auto paint item palette
Auto paint item is the brush you will choose during painting and use for editing the adjaceny rules in each auto paint rule.

#### auto paint mode options
![auto paint mode options](../_media/AutoPaint/mode_options.png ':size=50%')

Additional painting options specific for auto paint. 
> The most used command is **show auto paint hint (Alt+E)**.
During the painting process, you'll often toggle **show auto paint hint** to see through the instances been generated.


## 3. auto paint rules

rule detail overview

![rule detail overview](../_media/AutoPaint/auto_paint_rule_detail_overview.png ':size=50%')

#### Rule Detail
Check out [**Rule Detail**](AutoPaint/RuleDetail)

#### Rule Group
1. Show/hide rules within this group
2. Enable the whole group or not
3. Group name 
4. Add rule within this group

### order your rule
You can drag & drop group or rule to order them to meet your need.

> **The order for each rule matters a lot!** </br>
Rules are estimated through **top to bottom** sequence and by default it will stop on met. You'll need to place specific rules at higher order and the general rule at lower order.



## 4. test paint viewport

### Test paint area
Paint your items in this area to quickly preview what instances will spawn based on your rule group.
All painting process should be the same as normal paint. Select *auto paint item* and then paint it. (Fill and eyedropper tools and not implemented yet.)

> If you can't move floor up and down via **Z** or **C**, you need to open the preview scene setting at lease once. (the docked panel at right side) 

<span style="color:RED">RED block</span> may appear when you select any rule. It's a hint that these positions are where the rule met.

![met positions](../_media/AutoPaint/test_paint_area_met_positions.png ':size=50%')

### Item preview
Hint blocks for which cases for this rule would meet will appear is this region when there is any selected rule.
It's particularly useful to adjust spawn rotation to met different **mirror cases**.

![preview mirror cases](../_media/AutoPaint/adjacency_rules_visualization.png ':size=50%')
