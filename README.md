# Balloon-Shooting-Game-in-8086

# Abstract:

We aim to make a challenging but fun arcade game which will help ease the boredom of everyone during leisure
We will build this game using the assembly language available in the software emu-8086 and use loops, and manipulate flag registers to simulate a balloon shooting arcade game.

# ASSEMBLER AND CONCEPTS USED:

●EMU-8086

●8086 Instruction Set

●Procedures

●Looping

# Modules:
Key detection:
This module detects whether any key is pressed. If a key is pressed, it moves to the respective loop within the code.

Player movement:
This module detects when the ‘up’ and ‘down’ keys are pressed and the old position of the arrow is overwritten, and the new arrow appears above/ below the previous position.

Balloon:
This module renders new balloons by first hiding the old balloon if any, and only then will the new balloon be rendered.

Arrow:
When the spacebar is pressed, the arrow position is set at the player’s position and fired. When the arrow is fired, a limit is set on it, after which it hides. This prevents multiple instances of the arrow existing at once, which will prevent cheating and the final score will be determined only on the players’ skill

Score:
The player shoots a balloon if connected the hit counter goes up and triggers the system to make a sound. If not, then the miss counter goes up. After 9 misses the game is over.

After the game is over, the final page where the score is displayed.
