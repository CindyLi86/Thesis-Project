# Thesis-Project
Documentation of Cindy Li's Thesis Project. Contains all progress from working in Minecraft which creating a mod to address the self-harm treatment for teenagers.
## Game Design Doc
## Proposal
## References 
<https://www.jetlearn.com/blog/how-to-make-your-own-minecraft-mod>

<https://learn.microsoft.com/en-us/minecraft/creator/documents/createnpcs?view=minecraft-bedrock-stable>

<https://learn.microsoft.com/en-us/minecraft/creator/documents/gettingstarted?view=minecraft-bedrock-stable&tabs=android#commojang>

<https://www.pocketgamer.com/minecraft/minecraft-bedrock-commands/>

<https://github.com/microsoft/minecraft-samples>

<https://www.curseforge.com/minecraft-bedrock/addons/instant-structures-v6>
## Tools
<details>
  
  1. Mctool-creates entity (https://mctools.dev/#/behavior_packs/cind_myad/entities/skeleton.json)
  
  2. Dialogue designer-create NPC dialogues and scenes (https://jannisx11.github.io/dialogue-designer/)
</details>

## Development log
1.22 Literature 
<details>
  
1. Find relevant literature regarding fact of self-harm.
2. Literature of the ralationship between self-harm and videogames.
3. Literature of video games developed for other medical/psychological purpose.

</details>  
1.29 Game and Editer selection
<details>
  
1. Inquery sent to Thunder Lotus for licence to develope the mod.
2. Explore the Java and bedrock version of Minecraft.
3. Reached out to undergrad alumni for mod development.

</details>
2.6 Learn Mincraft
<details>
  
1. Get familiar with the operation of Mincraft.
2. Test out the comands and the syntax.
3. Exmeriment the dialogue implementation in the game.

</details>
2.12 Experiments in the Editor
<details>
  
1. Able to edit dialogue content in the dialogue window.
2. Able to create scenes for dialogue and connect them together by the command coded for button.

</details>
2.22 Storytelling implementation
<details>
  
1. Dialogues of part one created.
2. Scenes are linked.
3. Debug the link and loop of the dialogue of the scenes.
   
Still Need:

1. rename NPC by command or code to enable rename function.
2. players can pick up the dialogue from where they left.
3. color on key words.

</details>
2.26 Dialogue and implementation Problem fixed
<details>
  
1. Players can pick up the conversation.
2. Full dialogue wrote up.
3. Change the world time by command coded for buttons.
   
Still Need:

1. Create a loop for the last dialogue window to change the world time to the second day.

</details>
3.3 Mission implementation
<details>
1. Angry entity(monster) creates and working properly.

Still need: 

1. Set the summon position, attact area of the monster. 
2. Test the difficulty of the monster.

</details>
3.5 Mission and dialogue combined
<details>
  
1. Mission1: monster summon by command in dialogue complete.

Still need: 
1. Mission 3: choose house location for player and NPC.

</details>
3.10 Mission and dialogue combined
<details>

1. Full dialogue implemented. 
2. Mission 3: Instant house build add-on experience.
3. Font chosing.
Still need:
1. Can not edit the length of the button to have a full display of the text.

</details>
3.28 Text edit
<details>

1. Colored the text in dialogue.
2. Scene and logie connected
3. Final thesis proposal updated waiting for approval.

Still need:
1. Fire particles.
   
</details>
4.8 Fire particle and rename NPC
<details>

1. Tried to created widget for text enter to allow players rename NPC. Failed on this method. Alternatively, name of NPC becomes the relationship between player and NPC. still using /tag to establish connection.
2. Obtained set_on_fire script from microsoft bedrock learning website. Trained ChatGPT to modify the code from spawn a skeleton and set it on fire, modify the manifest.js to claim a higher version of editor. Created command and scriptevent of the script. Failed on this method.
3. Obtained flame particle json file from snowstorm and create scriptevent trigger for it. Failed triger the flame.
4. Using command block in minecraft with "/execute @a[tag=Burning]~~~particle Minecraft:lava_particle~~~" and /particle minecraft:~~~ to spawn the flame particle.Failed
5. All above scripteven are successfully called, but not thing happend.
6. Used /particle flame ~~~ to create fire in the game, prompt "request to create flame sent to all players". Still nothing visual or pysical damage happened to anyone. 

Still need:
1. Fire particles.
   
</details>

4.9 Fire particle
<details>

1. Successfully call the lava_particle repeatly through the command blcok.
2. Able to starts and pause the command by adding/removing tags to all entity.
3. Level design the places of gold block for players to collect.
4. Clearified the mission instruction in the dialogues
5. Fixed the problem of contents didn't fully display in the button.
6. pre-set the spaqning point for new player.
   

Still need:
1. Export the world as a template and run with all add-ons for tests.
   
</details>
