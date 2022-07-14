---

title: "Block"
tags:
  - CodeNinjas
---
# Block
- Create a block mod element, click the green plus and click Block
- Enter a new name for the block, there are certain restrictions to follow make sure they follow them. Also try not to include the word "Block" in the names
- Also do not use existing block names, e.g. Dirt, Diamond etc.

## Steps to actually make a block
1. Make new block texture - [[Codeninjas Camps/Minecraft Modding/Texture Making|Making Textures]]
2. Make block mod element - above
3. Change blocks texture - [[#Visual]]
4. Change blocks properties - [[#Properties]]
5. Save - top right corner Save Mod Element, green button

Following is a description of all the different tabs that are at the bottom. You can navigate to each of them by clicking each of them. The ? next to each thing will give some information when you click on it.

![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621174417.png]]

## Visual
- For the block textures, double click on each blank area and it'll let you choose from the textures that have been made. If you choose a Normal Block model on the right side, it'll let you choose textures for each side. This should be the setting by default.
- The Block Tint will apply the same tinting that applies to Grass blocks and Leaves etc.
	- The Tint Block Item? will apply the same tint to the actual item
- Block Base and Block Item Texture should be left alone always.
	- The Block Item Texture just lets you choose an item texture for the block, if they really want to do that for some reason.
	- The Block base setting is used to make [[Codeninjas Camps/Minecraft Modding/Not Full Blocks|stairs, slabs, leaves etc.]], but I need to look into how the textures need to actually be made for this
- For Block Model just leave it as Normal or Single Texture, the other options don't do much for us. Single texture applies the same texture to all sides. Normal lets you choose textures for each side.
- Rotation Mode lets you choose how the block rotates it's texture if it's placed from different sides. 
- Waterloggable only works on stairs, slabs, leaves, etc.
- Transparency should be left as default
- Special information empty

## Bounding Boxes
I don't know anything about these, avoid them for now

## Properties
Most of these are self explanatory or are explained by the ?
- In-game name - the name that shows up in game
- Material - Block material defines some base block properties such as reaction to pistons, water, plant growing options and more.     If you intend to use the block for ore, select ROCK material so the harvest level is properly applied.
- Creative Inventory Tab - what tab it shows up in in creative menu
- Hardness - higher value = longer to mine block
- Resistance - resistance to explosions
- Slipperiness - 0.6 is default, increase it to make it more like Ice
- Jump Factor - 1 is default, higher number increases jump height while on block, lower decreases
- Speed Factor - 1 is default, higher number increases speed while on block, lower decreases
- Luminance - Light level the block emits, from 0 to 15. 0 is none, 15 is like glowstone
- Light Opacity - how much light travels through the block. 0 means all light goes through, 15 means none goes through
- Has Gravity? - obvious
- Can walk through? - obvious
- Glowing? - obvious, glow like magma
- Is replaceable? - replaceable like flowers
- Custom Drop - what item the block drops. If left empty, it'll drop itself
- Drop amount - obvious
- Don't use loot table for drops
- Don't use creative pick item
- Tool able to destroy it - what tool is good at breaking this block?
- Tool harvest level - use the ? to understand the number
- Is Unbreakable?
- Sound set leave  as default, or change the Vanilla sound set to whatever sound set they want, it changes the sounds when you break it, place it, walk on it etc. to be like the type of block they choose. Don't use custom sounds

## Advanced Properties
Use the ? for these if they're really wanted, but most of them are beyond the scope of the camp. 

## Block Entity
Beyond scope of camp

## Energy & Fluid Storage
Beyond scope of camp

## Triggers
[[Codeninjas Camps/Minecraft Modding/Triggers|Triggers]]

## Generation
- Use Uniform distribution
- Click plus for dimensions to generate in, add Overworld
- Change average amount of ores in a group to a number between **1 and 16**
- Minimum and Max generation height are exactly what they say