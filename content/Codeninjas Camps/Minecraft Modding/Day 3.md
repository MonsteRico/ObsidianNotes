---
title: "Day 3"
tags:
  - CodeNinjas
---

# Day 3 Notes
## Mob Skin
- First thing to do for this is go to [www.minecraftskins.com](https://www.minecraftskins.com/)
- Click **editor** at the top
- **VERY IMPORTANT STEP HERE MAKE SURE THEY DO THIS**
- They need to click the button that says **Outer layer** and turn it off, or else the texture they' make wont work right in MCreator.
- Julian likely will know more about this if he has done it before
- Screen should look like this ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Outer Layer.png]]'
- The tools should be pretty self explanatory, but theres pencil eraser, eyedropper, bucket zoom etc
- Left click outside of the skin to pan around the skin and color in all parts
- Once finished they download it and save it to downloads folder

## Mob
- In MCreator, add a Living Entity mod element (green plus)
- They should not mess with the Entity Model section at all under visual and sound, nor the glow texture or the bounding box. I'd also recommend against the sounds, but they can if they want. ONly use the deafult sounds in the game, don't try and downlaod new ones. Make sure they choose their entity texture by clicking the green plus next to it and going to downloads and opening their texture they made and then select it from the dropdown
- In the behavior section they can change some of the general behaviors, same thing as the usual properties they can click teh question mark to see what it does. Important one at the top of Mob or Creature (aggressive or passive). They can edit the drop and equpiment here too, even using their own items.
- I'd skip particles and definitely skip inventory. Triggers are questionable, if you come up with ideas youre welcome to show them
- In the AI and goals, you can show off what some of the AI goals do, but the main thing to do here is get rid of everything except the top block and then click **AI Templates** and choose one to use, probably Basic passive, aggressive towards player, or aggressive when hit.
- Under the last section spawning they can change whether their new mob spawns like monsters, creatures, etc. Thats the only setting they should probably change on this page, but as per usual the question marks can explain the settings more.
## Break


- Create a custom tool with effects on it.

  - Create a texture for it, create the mod element, set up the properties however they want
  - In the triggers section of the tool or item, add procedures to **Living entity is hit with tool** and/or **When tool in hand tick**
  - ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Trigger 1.png]]
  - The procedure to add a simple potion effect looks like this, they know what the effects probably are by now.
  - A second is 20 ticks, make sure they keep that in mind when setting the ticks value
  - Any other general cool effects you can think of to walk them through, feel free to do so.



There isn't anything else to do for this day, I honestly think those two things will take a large amount of time for them to follow along with and/or mess around with. If you feel like theres too much time left you can add in stuff like adding effects to armor or doing more complicated effects etc. Otherwise I'd kind of just give them time to develop their mods, they know how to do items, blocks, tools, biomes (i think at least), mobs, and some basic effects on those things.
