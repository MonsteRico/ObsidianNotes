---

title: "Day 1"
tags:
  - CodeNinjas
---
# Day 1 - Intro, Ore, Tools
- Play Minecraft until everyone arrives and gets logged in, just have them log in or use our accounts for singleplayer. don't delay camp start by more than 15 minutes even if someone's late. **ever**. don't.
## Intro - 5 Min
- Chris will go over general rules
- As an icebreaker we do Name, Age/Grade, How long you've been playing Minecraft OR your favorite block/mob/item/biome/mod/etc.
- Have everyone start up MCreator and go into their Workspace.

## Talk about textures - 10 min
-  Close computers halfway while we talk about textures
- How does Minecraft do textures? (ask the ninjas)
- It uses sprite sheets basically, pulling from the sprite sheet whatever face of the block is needed and putting it in the game
- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621211602.png]]
- It also "unfolds" mobs to allow for their full textures to be displayed
- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621211644.png]]
- Can anyone figure out this mob? (ask, I think its a fox I honestly don't know.)
- Google Minecraft textures/Minecraft mob textures and show some more examples. Ask them what they notice and talk a bit about textures.
- Talk more about how Minecraft does textures if you know and/or are stalling for time for some reason

## First Block - 45 min
- First thing we will do modding-wise is make our first block
- We are not making an ore yet! We will definitely do that, but right now we are just getting used to MCreator and what it takes to make things in MCreator
- I recommend breaking the steps down and doing it as follows. Do each bullet point on screen and have them watch it, then have them do that part.
- Make a new Texture
	- [[Codeninjas Camps/Minecraft Modding/Texture Making|Texture Making]] - full details on texture making
	- Go to resources, create new texture, create texture. There are restrictions on the names for a lot of things, so make sure they pay attention
	- The editor is basically MS Paint, it should be easy to explain and for them to use
- Make block element
	- [[Codeninjas Camps/Minecraft Modding/Block|Blocks]] - Full details on block mod elements
	- Go back to the workspace, click the ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621212248.png]] green plus and make a block. 
	- On the first page (Visual section) they will have to put in their texture, that should be the only thing they have to mess with here
	- On the properties page they can change all the different settings on the block. You can go over some of the main ones like Hardness, In Game Name, and Creative Tab
	- Clicking on the question marks next to anything will bring up a little popup of what that thing does, **Make sure they know this it will save them and you time**
	- Don't spend too much time messing around with properties here, we want to get them to the point of seeing their new block in game. 
	- Make sure that before moving on everyone has the texture set up right, the in game name set up, and the creative tab set to something other than none
- Test It!
	- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621212732.png]]
	- Once they have saved their mod element, press the green play button located in the top right
	- This will open up a version of Minecraft with their mod already loaded into it.
	- They can make a new world to test in, go into their inventory, and should be able to find their block
	- Once you have confirmed that everyone is able to get their block in Minecraft, you can move on
- Messing with properties
	- Ask about the properties that the ninjas found (if any ended up with time to change them) and see what things they noticed
	- Go to the properties tab on the block and look more in depth at some of them.
	- Give them a little bit of time to change some properties, save, and test them out!

## First Recipe - 25 min
- After messing around with the block properties, we will now be making a Recipe for our block!
- [[Codeninjas Camps/Minecraft Modding/Recipes|Recipes]] - Full details on the recipes
- Make a new recipe and name it
- It'll bring up a crafting grid like this 
![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220621213350.png]]
- They can click on a spot in the grid and choose what goes in that spot
- They can also choose what goes in the output spot (our new block) on the right, and the amount of that output that is crafted
- They probably all understand how crafting works, it shouldn't be too hard for them to get a grasp of this
- The things on the left shouldn't need to be changed with the exception of the recipe type and cooking time in case of smelting
	- You can show them the Smelting recipes, although they probably won't need to smelt to make their block. That'll be useful when we get to ores if they're asking about it
	- In terms of the other recipe types, after we've made one for the block and tested it they can mess with them as well
- Save the mod element, go into Minecraft, and test the new recipe by actually making it in a crafting table

- Let them go back to MCreator and mess around with recipes and make new recipes for existing things
- They can also make more textures for blocks and make more blocks and recipes for them etc. there's already a lot they could do!

## Break - 15 min

## Ore Quiz - 5-10 min
- judge based on the kids in the camp whether this is needed
- this can be used as an activity to take up some extra time or get the camp to come back together
- if the kids are going a bit slow or need more time then this can be skipped
- [Minecraft Ores Quiz (sporcle.com)](https://www.sporcle.com/games/lmasta/minecraft-underground-ores)

## Ore/Ingot - 60 mins
- Textures
	- Next we are going to make a custom ore that generates *in the world*
	- First thing we need to do is create the textures
	- Go to the resources tab, create a new texture
	- This time we're going to use the template and find an ore template
	- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220623163306.png]]
	- They can also choose to create the template from a color or from scratch
	- Make sure they save the texture as a BLOCK and not an ITEM
	- Once the ore has been made, create another texture. For this template, search for either GEM or INGOT
	- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220623163540.png]]
	- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220623163549.png]]
	- They can change the color of these templates however they want
	- When they save the gem/ingot, make sure they save the texture as an ITEM texture and not a BLOCK texture
- The Ore
	- Once the textures have been made, go back to the mod elements tab
	- Create a new block for the ore and edit the properties how they want, mainly theyll want to look at the hardness and tool harvest level to drop. leave the custom drop empty
	- in the generation tab, click this plus and choose surface (thats the overworld)
	- ![[Codeninjas Camps/Minecraft Modding/Modding Pics/Pasted image 20220623163939.png]]
	- Average amount of ores in a group can be changed, but as it says it should be less than 32
	- Minimum and Maximum generation height can be changed as they want as well
	- Everything else should be left as default
- The Gem/Ingot
	- Back in the main workspace, make a new [[Codeninjas Camps/Minecraft Modding/Items|Item]]
	- They can choose the item texture and find the texture they made
	- There's a checkbox for glowing if they want it to glow for some reason
	- The main properties to mess with are the in game name and creative tab
	- Right now we aren't going to do weapons or tools or anything with our new gem, just have it be smeltable
- The Recipe
	- In the main workspace, make another recipe
	- This time change the Recipe type to Smelting.
	- They can then click on the boxes on the right and fill them in with their ore and the gem it makes
	- Save the recipe and hit the play button to test out the new ore!
- Testing
	- They should **generate a new world** in minecraft so that their ore can generate. They can then spend the rest of the time trying to find their new ore.
## Rest of the time
- The rest of the time can be spent searching for their new ore and freeplaying in Minecraft
