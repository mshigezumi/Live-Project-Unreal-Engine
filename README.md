# Live-Project-Unreal-Engine

## Introduction:

For the last two weeks with the Tech Academy I worked on a Live Project in Unreal Engine 4 which simulated a real world work environment in which I worked with staff on a level for a 3D puzzle and trap games located within a dungeon. I worked on a few stories in which I created my own level from the ground up, designing everything from the layout of the level to the puzzles and traps and their functionality.

## Stories:

This project consisted of seven stories which went through the full process of designing, creating, and implmenting my own level.

### Plan and Blockout Level:
This story had me planning and blocking out my level, this took a good amount of time due to not only having to design the level but keeping in mind what type of puzzles and traps I wanted and where I would place each one. In the end I settled on a three story dungeon with the bottom floor (which you spawn in) being an escape room with multiple puzzles and a trap. The middle floor is a maze and the top floor has four trapdoors which drop down into different parts of the maze on the floor below.

### Replacing with Meshes:
In this story I replaced the blocked out level with static meshes and finalized the architecture. For this story I had to figure out how to create meshes with the very limited tools for static mesh creation within Unreal Engine 4 in conjunction with free assets found from the asset store. This included making my own static meshes for walls and floors with actual thinkness (instead of just being flat) in an effort to get rid of seeing through the corners when viewed from certain angles, the trapdoors, doorways and a few of blueprints to enable the doors on the level to open and close.

### Adding Puzzles/Adding Traps:
These two stories took the longest due to me wanting to implement relatively complex puzzles, for example the escape room puzzles were all accessed, activated, deactivated, and completed via a single rotating switch. On top of that I had to make sure that the puzzles would work if done in almost any order. Considering this was my first real expeience developing in unreal doing all this took time to adjust to and learn. This included visual scripting, creating and using sockets, and creating blueprints and a blueprint interface which work together to get the desired effects and functionality of my planned puzzles and traps. I also tested extensively for these stories to ensure that while I was implementing the puzzles and traps no issues arrised from doing them in different orders and there was no issues with how they were accessed, activated, deactivated, and completed. Some issues I ran into where harder to solve than others, like using sockets on the static meshes to attach props and other blueprints was troubling due to not really knowing what the best way to implement what I wanted on top of the differences depending on what is being attached and/or activated.

### Adding Lighting:


### Adding Props:
By the time I got to this story I was reaching the end of the two weeks so I added some props in unused areas in a way that somewhat told a story. If I had more time I probably would of added more props, espcially to the escape room to make the puzzles harder to solve due to having more non-puzzle piece props in the area.

### Modifying, Testing, Refactoring, Iterating:
