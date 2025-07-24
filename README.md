# Dino-Game in Embedded C
This is Dino game which everyone have played in chrome but this project is Hardware implementation through Arduino and software implementation using Proteus software where code is written in Embedded C.

# About the Project
This project is a simple and fun implementation of the classic Chrome Dino game, built using Embedded C and simulated in Proteus. The idea was to recreate a minimal version of the game where a dinosaur jumps over obstacles like cacti, using a button as input.

It's designed to run on a microcontroller (like 8051 or AVR) and display the visuals on a graphical LCD or OLED. The game logic handles jumping, collision detection, and obstacle movement in real-time.

# Developed By
Dhruvin Pandya
(Feel free to update this with your name if you're using or modifying the project)

# Key Features
1. A playable dino game on a simulated microcontroller setup.
2. Real-time graphics on GLCD or OLED display.

3. Button-controlled jump action.

4. Basic obstacle movement and collision detection.

5. Clean and simple state machine-based logic.

# Tools and Technologies Used
1. Embedded C – Main programming language for game logic.

2. Proteus 8.x – Used for circuit simulation and visual output.

3. Microcontroller (8051, ATmega2560, or similar) – The "brain" of the game.

4. GLCD (128x64) or OLED Display – For rendering game visuals.

5. Push Button – Used to make the dino jump.

# Hardware (If You Plan to Build It Physically)
This game can be built on actual hardware too, with the following components:

1. 8051 or ATmega microcontroller

2. 128x64 GLCD or OLED display (SSD1306 works too)

3. Push button

4. Jumper wires, breadboard, power supply

# What's in the Project Folder
1. Dino.pdsprj – The Proteus simulation project file

2. main.c – Embedded C source code (if included)

3. dino.hex – Compiled code to load into the microcontroller

4. Bitmap or header files (for character and obstacle graphics)

# How to Run the Simulation
1. Open the Dino.pdsprj file in Proteus.

2. Load the .hex file into the microcontroller in the simulation.

3. Press the "Run" button in Proteus.

4. Use the button input to make the dino jump.

5. Try avoiding the obstacles and keep playing.

# Ideas for Improvement
This is a basic version of the Dino game. Here are a few ideas if you'd like to take it further:

1. Add a score counter and display it on-screen.

2. Include sound effects when jumping or on collision.

3. Introduce increasing difficulty levels as the game progresses.

4. Improve the obstacle generation and movement logic.

# Credits and Licensing
This project was created by Dhruvin Pandya as part of an embedded systems learning project. 

Feel free to use it, learn from it, or build upon it.
