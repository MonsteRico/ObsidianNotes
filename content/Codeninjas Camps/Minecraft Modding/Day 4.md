---
title: "Day 4"
tags:
  - CodeNinjas
---

# Day 4 MC Modding Camp
## Potion - 30 mins
- Really simple
- Make a **potion item** mod element
- Name the different potions at the top, add effects at the bottom.
	- The duration is in ticks, so 20 ticks per second \* x amount of seconds = the duration they want
	- Amplifier increases the level
- Theres no way to change the color of the potion that I can see, its just auto generated
## Paintings - 20 mins
- Very very simple to do
- Download any image from the internet, save it to downloads (somewhere they can get to)
- Make a new painting
- Click the plus to add a new image, find their image
- Click the dropdown and choose their image
- The hardest part about this is the painting size, it lets you choose any size but paintings usually go across full blocks
- A single block is 16x16, so if they want it to be a 2x2 of blocks, it needs to be 32x32 pixels, if they want it to be a 4x4 of blocks, 64x64 and so on.
- Quick conversion table
- Width X Height in MCreator/in pixels ----- Width X Height in Minecraft/Blocks
	- 16x16 --- 1x1
	- 16x32 --- 1x2
	- 32x16 -- 2x1
	- 32x32 --- 2x2
	- 64x64 --- 4x4
- I don't think Minecraft does any other sizes, but you get the idea those are the intervals
## Food - 30 mins
- Owen said that when he did the camp they really liked making new food items, so I figured leave this for last and let them mess around with it the most and make what they want.
- Food stuff is pretty basic, it's make texture **save as Item texture**, make Item mod element, go to food properties and make it a food and change the properties
## Break - 15
## Free Create - rest of time
- If more structure is needed or another goal is needed, go through dimensions
## Dimension
- They will need textures for the item used to light the portal and for the portal itself
- Also will need a block to use for the portal frame, have to make the block mod element if they are making their own
- Properties
    - I"d recommend normal world gen
    - Set a main filler block and fluid block
    - Add any biomes they want to appear in this dimension (could even be the ones theyve made)
    - Sky/fog color can be changed
    - Whether to allow sleeping or not
    - All the check marks are kind of obvious
- Portal Section
    - Make sure dimension portal is enabled
    - Portal frame block - this is the equivalent of obsidian for the nether portal
    - Particles - the particles coming off the portal
    - Luminance - how much it lights up
    - Igniter item name - name of the item used to ignite the portal eg flint and steel
    - set the textures for the igniter item and the block at teh bottom
- As far as I can tell theres no way to craft the item for the custom portal, itll have to be a creative only thing i think
- This entire thing is likely to be buggy but if they wanna do it the option is there

