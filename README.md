**DISCLAIMER:** this project was done for educational purposes, e.g.: to improve C++/Python programming language skills and learn about possibilities to create GUI's with a goal to facilitate user interface with the microcontroller.

# Introduction
This project utilizes Arduino Uno to run the main code, 8x8 LED Matrix MAX7219 to create a graphical representation of the snake game and PC to act as an interfrace between you and the game by running a python script. Here is a list of different subjects that this project touches upon:
1. C++
2. Python (GUI)
3. Arduino Uno
4. Electronics

# How it works?
As mentioned earlier, Arduino Uno runs the main code, it receives commands such as UP, DOWN, LEFT, RIGHT from user input and translates these commands to switch on LED's in a certain order to represent movement of the snake. The control of the LED matrix is accomplished by using the "MaxMatrix" library. User sends commands by pressing arrow keys on the keyboard of his PC. For this to work, Arduino has to be connected via a cable to the PC in order to establish serial communication between the two. After turning Arduino on, the user will require to run a python script that is responsible for GUI.


# Required hardware
1. Arduino Uno R3
2. personal computer
3. USB cable A to B
4. breadboard
5. jumper wires
6. MAX7219 8x8 Matrix Display Module

# Instructions of use
1. make the necessary connections on the breadboard as shown in the schematic
2. connect Arduino and PC with USB cable ( after connection you should see a snake moving across the LED matrix )
3. launch 8x8snake.exe on your PC, and input what port is Arduino connected to
4. play!
