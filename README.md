This project was completed in Eclipse during my Spring 2017 semester with Aasish Basani (listed as a collaborator) for my Fundamentals of Computer Science II course.

The directions for the game are as follows:
- The object of the game is to collect all of the parts to the helicopter (pink circles) and return to the helicopter icon
- One player moves with the arrow keys and the other with the W, A, S, and D keys and they are working together
- The game starts with the players randomly placed, the parts scattered, and the helicopter at the highest point
- The water rises as time passes and this is shown with the blue creeping further up the island
- The spaces turn red when they are at a low enough point to flood
- If the players can not collect all of the parts and both return to the helicopter the game is lost
- If a player is on a space that then turns to water the game is lost
- To change the game to different modes press the r key (diamond island with random heights) or the m key (diamond island with uniform heights)

To run the game in Eclipse:
- Download the code as a zip
- Create a new java project
- Add the two jar files as external libraries
- Create a new file in the src folder either using the ForbiddenIsland.java existing file or pasting it in to a new file
- Drag and drop the 3 image files into the package explorer, specifically on the containing folder of the entire project
- The three image files should now appear under the referenced libraries tab in the package explorer
- Create a java application run configuration with the main class being tester.Main and for the program arguments input ForbiddenIslandExamples
- Run the program to play the game
