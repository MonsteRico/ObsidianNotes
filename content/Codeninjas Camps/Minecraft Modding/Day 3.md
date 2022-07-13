---
title: "Day 3"
tags:
  - CodeNinjas
---

# Day 3 Notes
## Custom Tool Effects - 30 mins
- Have the ninjas follow along or watch as you create a pickaxe that gives you haste while you hold it.
	- To do this, follow everything below, just use haste instead of speed and make the pickaxe texture and tool mod element live
	- This gives them a chance to see it done once or a chance to do it once guided and then do it on their own with a new tool or to their old ones
- Create a custom tool with effects on it.
  - Create a texture for the tool, create the mod element, set up the properties however they want
  - In the triggers section of the tool or item, add procedures to **Living entity is hit with tool** and/or **When tool in hand tick**
  - ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Trigger 1.png]]
  - The procedure to add a simple potion effect looks like this, they know what the effects all do.
	  - For example, the code above will give speed level one for 3 seconds while the tool is in their hand
	  - A second is 20 ticks, make sure they keep that in mind when setting the ticks value
  - For a tool in hand tick, use lower tick values so when the tool stops being held, the effect goes away

## Ranged Weapon - 30 mins
- Bow and Arrow type ranged weapon
- Make a texture for your bow part (could be a type of gun, bow, crossbow etc), **save as Item texture**
- Make a texture for the projectile (bullet, arrow etc) **save as Item texture**
- In Mod elements, create an Item for the projectile. Only give it the texture, don't change any other settings for this item, the damage is set by the Ranged item mod element
- Create a Ranged Item
  - Choose the texture they made
  - Item Animation, what the item will act like when they use it.
  - Max stack size 1
  - Item for ammo, set to the item they just made
  - Shoot constantly while active - optional for their weapon
  - Item usage count - durability
  - they can change the sound if they want
  - Under the projectile settings at the bottom, they can change the power, damage, knockback etc.
  - Main thing to change there is the **Item representing texture of projectile**, change it to the item/texture they made.
  - Triggers if they want to mess with them
- Add recipes for both the ammo and the weapon
## Snowball Type Item (with bonus code) - 30 mins
- Examples could be, dodgeballs, pokeballs, stones, anything you can throw basically
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
  - As a bonus to use some more time if needed, we can add some code to spawn a mob where the projectile lands
	  - In the Triggers section, we make a procedure that runs When projectile hits block.
	  - ![[Pasted image 20220713162813.png]]
	  - Press that plus button and then create with the default name
	  - The code will look like this
	  - ![[Pasted image 20220713162934.png]]
	  - They can change the living entity to any Minecraft mob they know of
	  - They're also welcome to mess with the code more and try making different things happen, some of the older campers might be able to make some cool things.
	  - Encourage experimentation, show maybe placing a block at the x, y, z, instead of spawning a mob. (It's a "Place x at x y z" block, under Block Management section). Try making it do effects when it hits something instead of when it hits a block, like the custom weapon before.
## Break - 10-15 mins
## Minecraft Mobs
- Talk through these questions and have the ninjas answer them
- What are Mobs in Minecraft? (They are animals, creatures, enemies etc)
- What are some examples of mobs? (Sheep, Drowned, Ender Dragon etc, don't let them get TOO off track b/c they probably will)
- What Mob groups are there? Which mobs have similar AI? (Passive - sheep, cows, Neutral - bees, wolves, Aggressive - zombies, skeletons, Wandering - bats)
- We talked about mob textures on day one, but quickly review them here
- - ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621211644.png]]
- We know Minecraft mobs have textures unfolded kind of like this. Player textures are also done the exact same way. Because of this, we can use any player skin as a Mob skin and turn it into a mob.
## Mob Skin- 30 mins
- First thing to do for this is go to [www.minecraftskins.com](https://www.minecraftskins.com/)
- Click **editor** at the top
- **VERY IMPORTANT STEP HERE MAKE SURE THEY DO THIS**
- They need to click the button that says **Outer layer** and turn it off, or else the texture they' make wont work right in MCreator.
- Screen should look like this ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Outer Layer.png]]'
- The tools should be pretty self explanatory, but theres pencil eraser, eyedropper, bucket zoom etc
- Left click outside of the skin to pan around the skin and color in all parts
- Once finished download it and save it to downloads folder, download button is on the right
- Have them make a skin for the mob they want to create. Some examples could be a new type of zombie, a herobrine type mob etc. basically anything that stands on two legs and looks kind of like a player.
- Making textures for any other kind of mob is difficult, as such we are only able to make mobs that look kind of like players. However, the AI of these mobs can be like any other mob in the game. You could have a standing Pikachu, but the AI is like that of a Wolf.
## Mob - 45 mins
- In MCreator, add a Living Entity mod element (green plus)
- They should not mess with the Entity Model section at all under visual and sound, nor the glow texture or the bounding box. I'd also recommend against the sounds, but they can if they want. 
	- Only use the default sounds in the game, don't try and download new ones. 
- Make sure they choose their entity texture by clicking the green plus next to it and going to downloads and opening their texture they made and then select it from the dropdown
- In the behavior section they can change some of the general behaviors, same thing as the usual properties they can click the question mark to see what it does. 
	- **Important one at the top of Mob or Creature (aggressive or passive).** 
	- They can edit the drop and equipment here too, even using their own items.
- I'd skip particles and definitely skip inventory. Triggers are questionable, if you come up with ideas you're welcome to show them
- In the AI and goals, you can show off what some of the AI goals do, but the main thing to do here is get rid of everything except the top block and then click **AI Templates** and choose one to use, probably Basic passive, aggressive towards player, or aggressive when hit.
- Under the last section spawning they can change whether their new mob spawns like monsters, creatures, etc. That's the only setting they should probably change on this page, but as per usual the question marks can explain the settings more.
- Once they have made a mob, go in the game and spawn it. Play around with it, try editing properties, make more mobs etc.