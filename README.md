# Arduino-LCD-running-game.
16x2 LCD Runner Game using Arduino Uno with custom sprites, interrupt-based jump control, scrolling terrain, and collision detection.

🕹️ Arduino LCD Runner Game

This project is a 16x2 LCD-based runner game developed using Arduino Uno and the LiquidCrystal library. The game features a running hero character that must jump over randomly generated obstacles. The player uses a push button to control the jump action.

🚀 Features

Custom LCD character sprites (running and jumping animation)

Smooth scrolling terrain

Random obstacle generation

Interrupt-based button control

Collision detection system

Score tracking based on survival distance

Game over and restart functionality

🛠️ Hardware Used

Arduino Uno

16x2 LCD Display

Push Button

Potentiometer (for contrast control)

Breadboard & jumper wires

💡 How It Works

The terrain is stored in two character arrays (upper and lower rows).

The terrain shifts left to create a scrolling effect.

A push button is connected using an external interrupt for responsive jumping.

The hero movement is implemented using a finite state machine.

Collision is detected by checking overlap between hero position and terrain blocks.

Score increases as the player survives longer.

🔧 Programming Language

Arduino C++ (based on C/C++)
