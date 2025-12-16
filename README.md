# DIY Interactive Smart Chess Board

Welcome to the DIY Interactive Smart Chess Board project! This repository contains all the necessary code and documentation to build your own smart chess board.

## Project Overview

Our project aims to create an interactive chess board that can:
*   Detect piece movements
*   Guide players with legal move indications via LEDs
*   Guide players with legal move indications
*   Potentially play against an AI (future development)


## Programming 
* ChessLogic.py: Logic/Rules: Contains the rules of chess with a public interface for verifying chess logic, mainting game data/state.
* LEDController.py: Interfaces with the Microcontroller to control LED colors/state/brightness etc.
* SensorReader.py: Interfaces with the Microcontroller to read sensor states from the shift registers.
* GameManager.py: Main game loop to drive the system.


