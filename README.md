Project 3 Planning 

The Game: http://www.dvgiochi.net/bang_the_dice_game/BANG!_dice_game-rules.pdf
Each player has a role that define its goal card:
• Sheriff: must eliminate all Outlaws and the Renegade(s); • Outlaws: must eliminate the Sheriff;
• Deputies: must help and protect the Sheriff;
• Renegade: must be the last character in play.


End of the Game
The game ends immediately if:
a) The Sheriff is eliminated: If a Renegade is the only one alive, he wins. Otherwise, all Outlaws win as a team.
b) All the Outlaws and Renegades are eliminated: The Sheriff and all Deputies win as a team.




Classes
Game
  Create Linked List to control turn order (library)
    Sheriff will be player 0
  Player death (link around dead player)
  Randomly assign role to each player excluding sheriff
  Randomly assign character to each player including sheriff
  Keep track of number of each role
  Keep track of number of arrows left in pile
    If none, all players lose 1 LP

		START
Handle the 5 dice results logic
Prompt user for reroll (AI no rerolls)
Interact with player classes based on die results 
After actions executed
Check for ending conditions
element->next

Player Class (each element in the linked list)
Attributes
Role
Character
LifePoints (if 0 report to Game class to remove player from linked list)
	

Dice class
Random number 1 - 6 (order on the rules) for interpretation


Character class (Super)
16 subclasses with specifics for each character
BART CASSIDY (8)
BLACK JACK (8)
CALAMITY JANET (8)
EL GRINGO (7)
JESSE JONES (9)
JOURDONNAIS (7)
KIT CARLSON (7)
LUCKY DUKE (8)
PAUL REGRET (9)
PEDRO RAMIREZ (8)
ROSE DOOLAN (9)
SID KETCHUM (8)
SLAB THE KILLER (8)
SUZY LAFAYETTE (8)
VULTURE SAM (9)
WILLY THE KID (8)

Role Class
Sheriff
Deputy
Renegade
Outlaws



GUI
Players
Arrows in front of them
Roll dice
Actions
Piles



Timeline
First Meeting,March 31, 2020	
Plan proj for most part
Sam: Start Game class
Braden: Start looking at GUI setup
Tyler: Dice class
Rafael: Start Role/Characters class 


Second Meeting, April 2, 2020
Go over work done
Questions 
