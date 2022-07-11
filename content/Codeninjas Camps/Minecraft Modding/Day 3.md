---
title: "Day 3"
tags:
  - CodeNinjas
---

# Day 3 Notes
## Custom Tool Effects - 30 mins
- Create a custom tool with effects on it.
  - Create a texture for it, create the mod element, set up the properties however they want
  - In the triggers section of the tool or item, add procedures to **Living entity is hit with tool** and/or **When tool in hand tick**
  - ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Trigger 1.png]]
  - The procedure to add a simple potion effect looks like this, they know what the effects probably are by now.
  - A second is 20 ticks, make sure they keep that in mind when setting the ticks value
  - Any other general cool effects you can think of to walk them through, feel free to do so.

## Ranged Weapon - 30 mins
- Either do both of these options or just one, your pick
- Bow/Arrow type ranged weapon
- Make a texture for your bow part (could be a type of gun, bow, crossbow etc), **save as Item texture**
- Make a texture for the projectile (bullet, arrow etc) **save as Item texture**
- In Mod elements, create an Item for the projectile. Only give it the texture, don't change any other settings for this item
- Create a Ranged Item
  - Choose the texture they made
  - Item Animation, what the item will act like when they use it.
  - Max stack size 1
  - Item for ammo, set to the item they just made
  - Shoot constantly while active - optional for their weapon
  - Item usage count - durability
  - they can chagne the sound if they want
  - Under the projectile settings at the bottom, they can change the power, damage, knockback etc.
  - Main thing to change there is the **Item representing texture of projectile**, change it to the item/texture they made.
  - Triggers if they want to mess with them
- Add recipes for both the ammo and the weapon
## Snowball Type Item - 30 mins
- Make texture for the snowball type thing **save as Item texture**
- Create a ranged item
  - Set the max stack size to something other than 1, it's how many can be in a stack. eg snowballs can have 16 in a stack
  - set item animation to none
  - set shoot constantly while active to true
  - **set item usage count to 0**
  - set the sound if they want to change it
  - **IMPORTANT PARTS HERE**
  - Set the item for ammo to _anything_ and the **Item representing texture of projectile** under projectile at the bottom to anything.
  - After they save mod element, go back into it and set those two things to the ranged item they just finished making.
	- basically MCreator won't let you choose the item youre currently making, so they have to save it and then go back in to choose that item
  - Rest of the settings act the same
  - Recipe as per usual

## Break - 10-15 mins
## Minecraft Mobs
## Mob Skin- 30 mins
- First thing to do for this is go to [www.minecraftskins.com](https://www.minecraftskins.com/)
- Click **editor** at the top
- **VERY IMPORTANT STEP HERE MAKE SURE THEY DO THIS**
- They need to click the button that says **Outer layer** and turn it off, or else the texture they' make wont work right in MCreator.
- Julian likely will know more about this if he has done it before
- Screen should look like this ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Outer Layer.png]]'
- The tools should be pretty self explanatory, but theres pencil eraser, eyedropper, bucket zoom etc
- Left click outside of the skin to pan around the skin and color in all parts
- Once finished they download it and save it to downloads folder

## Mob - 45 mins
- In MCreator, add a Living Entity mod element (green plus)
- They should not mess with the Entity Model section at all under visual and sound, nor the glow texture or the bounding box. I'd also recommend against the sounds, but they can if they want. ONly use the deafult sounds in the game, don't try and downlaod new ones. Make sure they choose their entity texture by clicking the green plus next to it and going to downloads and opening their texture they made and then select it from the dropdown
- In the behavior section they can change some of the general behaviors, same thing as the usual properties they can click teh question mark to see what it does. Important one at the top of Mob or Creature (aggressive or passive). They can edit the drop and equpiment here too, even using their own items.
- I'd skip particles and definitely skip inventory. Triggers are questionable, if you come up with ideas youre welcome to show them
- In the AI and goals, you can show off what some of the AI goals do, but the main thing to do here is get rid of everything except the top block and then click **AI Templates** and choose one to use, probably Basic passive, aggressive towards player, or aggressive when hit.
- Under the last section spawning they can change whether their new mob spawns like monsters, creatures, etc. Thats the only setting they should probably change on this page, but as per usual the question marks can explain the settings more.