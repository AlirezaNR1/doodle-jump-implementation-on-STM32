# doodle-jump-implimentation-on-STM32

## Introduction
implements the classic Doodle Jump game using C programming on an STM32F3Discovery board. The game utilizes a 20x4 character display, a keypad for navigation and character control, a buzzer for sound effects, a 7-segment display for scoring, and a volume control for adjusting game difficulty.

## Components
### Hardware Components:
- STM32F3Discovery board
- 20x4 Character Display: Main display for the game level.
- Keypad: Used for navigation in the menu and controlling the character.
- Buzzer: Produces different sounds during gameplay.
- 7-Segment Display: Used for calculating and displaying the player's score.
- Volume Control: Adjusts the game's difficulty level.

## Rules and Mechanics
The game mechanics are as follows:
- The 20x4 display serves as the main level, generating random platforms uniquely each time.
- The doodler starts from the first row of 20 rows and jumps 7 cells each time.
- The player can move the doodler left and right to land on other platforms to ascend.
- Broken platforms cause the player to fall until landing on a normal platform.
- Enemies can be shot using the keypad.
- Black holes must be avoided; contact results in the player losing.
- Some platforms have springs that propel the doodler 14 cells higher.
- Scores increase with ascent, with higher difficulties granting more points.
- 10 difficulty levels adjust platform frequency and enemy appearances.
- A high-score system is accessible after losing.

## Features
- **STM32 Integration**: Utilizes the STM32 board's capabilities for game implementation.
- **Button Controls**: External keypad is mapped to control the game character.

## Demonstration
https://github.com/AlirezaNR1/doodle-jump-implimentation-on-STM32/assets/141549257/9ffbd127-6cfe-418b-86a9-d6ffcaad5dc2



Feel free to fill in each section with more details specific to your project. This should serve as a good starting point for your README file on GitHub!
