# Treasure Hunt
---

## Objective
---

Complete the functionality for the treasure hunt minigame within a team's game. The task is to complete the logic for after users decide if they want to search left or search right.

## Features  
---

1. When the player chooses to go **left**, implement the following logic:
       
    * **If the player is on an odd step**: print "_Encounter a hidden trap!_" and decrease the player's health by 20.
      
    * **If the player is on an even step**: print "_Found a secret shortcut!_": Increase the player's score by 20.
    
    
2. When the player chooses to go **right**, implement the following logic:
       
    - **If the player is on an odd step**: print "_Discover hidden treasure!_": Increase the player's score by 50.
      
    - **If the player is on an even step**: print "_Encounter a wild creature!_": Decrease the player's health by 30.

3. When the player reaches 150 total points, then they've found the treasure. 
  
    - print "_Congratulations, treasure found!_"
  
    - Adjust the while loop to exit the game once a player has won.
