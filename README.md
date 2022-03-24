# Live-Project-Unreal-Engine

## Introduction:

For the last two weeks with the Tech Academy, I worked on a Live Project in Unreal Engine 4 which simulated a real-world work environment in which I worked with staff on a level for a 3D puzzle and trap games located within a dungeon. I worked on a few stories in which I created my own level from the ground up, designing everything from the layout of the level to the puzzles and traps and their functionality.

## Stories:

This project consisted of seven stories that went through the full process of designing, creating, and implementing my own level.

### Plan and Blockout Level:
This story had me planning and blocking out my level, this took a good amount of time due to not only having to design the level but keeping in mind what type of puzzles and traps I wanted and where I would place each one. In the end, I settled on a three-story dungeon with the bottom floor (which you spawn in) being an escape room with multiple puzzles and a trap. The middle floor is a maze and the top floor has four trapdoors that drop down into different parts of the maze on the floor below.

### Replacing with Meshes:
In this story, I replaced the blocked-out level with static meshes and finalized the architecture. For this story, I had to figure out how to create meshes with the very limited tools for static mesh creation within Unreal Engine 4 in conjunction with free assets found from the asset store. This included making my own static meshes for walls and floors with actual thickness (instead of just being flat) in an effort to get rid of seeing through the corners when viewed from certain angles, the trapdoors, doorways, and a few blueprints to enable the doors on the level to open and close.

### Adding Puzzles/Adding Traps:
These two stories took the longest due to me wanting to implement relatively complex puzzles, for example, the escape room puzzles were all accessed, activated, deactivated, and completed via a single rotating switch. On top of that, I had to make sure that the puzzles would work if done in almost any order. Considering this was my first real experience developing in unreal doing all this took time to adjust to and learn. This included visual scripting, creating and using sockets, and creating blueprints and a blueprint interface that work together to get the desired effects and functionality of my planned puzzles and traps. I also tested extensively for these stories to ensure that while I was implementing the puzzles and traps no issues arose from doing them in different orders and there were no issues with how they were accessed, activated, deactivated, reset, and completed. Some issues I ran into were harder to solve than others, like using sockets on the static meshes to attach props and other blueprints were troubling due to not really knowing the best way to implement what I wanted on top of the differences depending on what is being attached and/or activated.

### Adding Lighting:
For this story, I added torches, chandeliers, candle holders, and fires. Some of these had point lights attached to see in the completely dark room. Where applicable they were attached to puzzles and linked into the blueprints. I also carefully placed lights for the second and third floor to possibly misdirect the player when completing the final timed puzzle which had them dropping through each of the trapdoors to close them (while open they blocked the way forward) and go through the maze again to see if they were quick enough to escape the dungeon. I also added some lighting outside so you see the sunset when the player gets out.

### Adding Props:
By the time I got to this story I was reaching the end of the two weeks so I added some props in unused areas in a way that somewhat told a story. If I had more time I probably would have added more props, especially to the escape room to make the puzzles harder to solve due to having more non-puzzle piece props in the area.

### Modifying, Testing, Refactoring, Iterating:
This final story I was able to do quite quickly since while creating the level I was being very meticulous with everything I worked on, so almost everything was already in a satisfactory state, being tested, already refactored multiple times, and improved on when I first worked on them. There were a few smaller things that I changed like how some props rotated, and the initial placement of some of the puzzle pieces, I also updated a couple of the earlier visual scripts with the knowledge I gained while working through the blueprints.

## Images:
![BP_Gargoyle_Statue](https://user-images.githubusercontent.com/71560004/159940396-73789b64-594b-4a74-a4c2-0d4d048600b7.png)
Here is an image of the event graph for the blueprint of the gargoyle statue, the main interactable for the first set of puzzles.

![BP_Skeleton](https://user-images.githubusercontent.com/71560004/159950758-0d669eba-075a-4531-8592-a1c8b6d722b6.png)
![BP_Alter](https://user-images.githubusercontent.com/71560004/159950744-dd75eabc-c102-480e-be55-67a46eb6387d.png)
![BP_Cell_Door1](https://user-images.githubusercontent.com/71560004/159950751-5646ebf9-c644-422e-bcf8-528ee9c7c2af.png)
![BP_Trapdoor](https://user-images.githubusercontent.com/71560004/159950753-199c3cfe-3a32-4158-8abc-bfac30071524.png)
