# apcs-wall
AP Computer Science final project

Wall Simulator
By Anthony Ma and Daniel Wu
5/9/2016

Introduction: 
This program is a game where the player character builds and manages the building of a wall to keep an evil alien species from eating the village. The overall rules are that the player cannot directly build the wall or interact with the supplies or aliens. The program would ideally be used by people who want to play a game. The primary features for our program is an intuitive AI controlled population that performs the construction, defense, maintainence, and assault of the wall.

Controlls: 
Controll workers and guards by clicking and dragging left such that a box is formed over a certain area. Workers and Gaurds inside are now under controll and should be assigned different tasks with the right click. Should not be able to directly control aliens. 

Goals: 
Must Have
- Menu with buttons and options that include instructions and settings 
- One type of worker to maintain the wall
- One type of defense to bolster wall defenses
- One type of gaurd to defend the wall and man the defense structure
- Set AI for gaurd and workers (gaurd automatically shoots aliens when in range, workers auto fix broken walls when in range) 
- One type of Alien enemy with a set behavior

Want to Have
- Interactive settings that can change the color/appearance of different wall parts
- Individual worker classes that have different sprites and functions
- Multiple types of Aliens with different sprites and behaviors
- Different types of gaurds that have multiple behaviors for different defense setups
- Map to show alien setup 

Stretch
- Get networking to make it so that two people can play the game where one controlls the Ai and the other controlls the human defenses
- Allow for terrain interactions where the player can alter the wall 
- Some sort of diversion from the game that allows the humans to go on the defensive against the aliens
- Mod capabilities, allowing the player to change the source code directly
- Random events within the game that can completely change the situation with different variables
- Interaction with out of settlement variables 

Classes:
DrawingSurface (PApplet drawings)
Wall (Main runner)
WallPiece (Represents the wall in the game)
Person (Represents a person)
Worker (Represents a builder of the wall)
Guard (Represents a guard of the wall)
Player (Represents the player of the game and his/her resources)
Alien (Represents an alien)

Responsibility List:
Anthony will do DrawingSurface, Wall, Wallpiece, Player, + sprites 
Daniel will do Person, Worker, Gaurd, Player
