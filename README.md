# Text-Based Adventure Game 
The game is implemented using **formal languages and automata theory**. It's an **FSM** (finite-state machine) that can change from one state to another in response to input.The goal of the game is to discover the secret exit, navigating through a map, formed of different rooms that contain unique challenges and rewards. The states of the automaton are represented by the rooms of the map, and the final state is the secret exit. Commands are checked for correctness by constructing a **CFG**.

## Game Map
![image](https://github.com/user-attachments/assets/74ff0e74-adf8-4b7c-8514-972acc774794)

## Game commands
• go [room name]: Moves the player to the specified room if it is adjacent
and the necessary conditions (e.g. having a certain item) are met.
• look: Provides a description of the current room and the adjacent rooms.
• inventory: Shows the items currently in the player’s possession.
• take [item]: Allows the player to pick up an item found in a room.
• drop [item]: Allows the player to drop an item from their inventory into
the current room.

## Initial Configuration
In the initial setup, the following items are located in the corresponding rooms:

![image](https://github.com/user-attachments/assets/256fece9-11a0-4eff-8a60-9958e769070f)

Each room requires a specific item to enter. For example, to
enter the Armoury from the Entrance Hall, the player needs the ’key’. These
conditions create a logical progression and challenge in the game.
