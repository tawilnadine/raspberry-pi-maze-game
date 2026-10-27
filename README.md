# Raspberry Pi Maze Game

An interactive maze game built with Python and Raspberry Pi.
The player uses a joystick to navigate an 8 × 8 maze.
An LCD, RGB LED, and buzzer provide feedback during the game.

## Features

- Joystick control for moving up, down, left, and right.
- LCD messages showing game feedback and step count.
- Red light and buzzer feedback when hitting a wall.
- Green light when making a valid move.
- Up to three hints showing available movement directions.
- MQTT messages reporting the current position and movement.

## Hardware

- Raspberry Pi
- Joystick connected through an analog-to-digital converter
- 16 × 2 I²C LCD
- RGB LED
- Push button
- Buzzer

## Project files

- `maze.py`: Python code for the game.
- `Maze.xlsx`: Spreadsheet accompanying the project.
- `Project Maze_game report.pdf`: Project report.

## Running the game

This project requires a Raspberry Pi with the connected hardware.
The code uses GPIO and I²C communication and expects an MQTT
broker running on localhost at port 1883.

Detailed wiring and installation instructions will be added.

## My contribution
- The project idea
- Programming and connecting the devices
- Writing the report
