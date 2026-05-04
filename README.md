Creating a game with an Arduino
===================================
Arduino C++ Code that makes it run a game with a Main Menu, Options, and a Playable State.
The circuit fills up both of the Arduino's Interrupt slots, and contains a switch that serves as an ON/OFF Switch, and two push buttons that are labeled as A and B Buttons.
The Switch has the highest interrupt possible, with both the push buttons occupying the second interrupt slot.

Features
-
- Main Menu System allowing the player to choose from Play, Options, or Exit.
  - Options contains a setting that controls the game speed.
- Game is based off of the Dinosaur Run Game, which has the player jumping over obstacles as their score increases over time until they run into an obstacle.
  - Game Speed increases over time.

How to Build
-
For those wanting to recreate, test, and modify this project, the following will be needed:

- Arduino UNO R3
- Hosyond 0.96 inch I2C OLED Display
- 2 Push Buttons
- 1 Switch
- 15 M-M Wires
- 2 10k Ohm Resistors
- 1 1k Ohm Resistor
- 2 Diodes
- Breadboard

<img width="545" height="633" alt="Screenshot 2026-05-02 140154" src="https://github.com/user-attachments/assets/7b5de6e2-7e83-46be-9886-91cf227f5ecf" />

<img width="659" height="577" alt="image" src="https://github.com/user-attachments/assets/dffe44be-2c11-4846-b4a4-9f4f85e2238c" />

Construct the circuit as shown with the circuit diagram and circuit photo above.
Once constructed, and ArduinoIDE is booted up, download the SSD1306 Arduino Library (https://github.com/vkumpan/SSD1306), which will be necessary for activating and displaying text on the OLED Display.

From there, the circuit is now done. The button connecting to the Arduino's D8 Slot is considered to be the "A" button, with the button connected to D9 being the "B" button. In the menu, the A button will select the current option, while pressing B will change and cycle through to the next displayed option.
To those interested, feel free to play around, modify, and try adding new features to better understand the Arduino and what can be done with it.
