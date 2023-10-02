# TicTacToe
# TicTacToe MATLAB App README

## Overview

This MATLAB App, named "TicTacToe," is designed for playing the classic Tic-Tac-Toe game. It allows two players to take turns making moves on the game board. The players can choose their fate, either as "Player 1" (represented by red) or "Player 2" (represented by black). The goal of the game is to get three of their respective colored boxes in a row (horizontally, vertically, or diagonally) before the opponent does.

### Author

- **Author**: [Jonathan Glenn]
- **Date**: [12-5-20]

## Description

The `TicTacToe` app is built using MATLAB's App Designer. It provides a graphical user interface (GUI) for the Tic-Tac-Toe game. The key components and features of this app are as follows:

### Properties

- `UIFigure`: The main MATLAB figure window.
- `TicTacToeLabel`: A label displaying the title of the game.
- `ChooseFateDropDownLabel` and `ChooseFateDropDown`: Allows players to choose their fate as "Player 1" or "Player 2."
- `TextAreaLabel` and `TextArea`: A text area providing instructions and game information.
- `UIAxes`: A UIAxes component where the Tic-Tac-Toe game board is displayed.

### Callbacks

The app includes callback functions that handle component events, primarily related to mouse clicks on the game board. When a player clicks on a position on the board, their chosen color (red or black) is placed in that position, indicating their move.

## Usage

To play the Tic-Tac-Toe game using this app, follow these steps:

1. Open MATLAB.
2. Create an instance of the `TicTacToe` class by running the app or using the app's class constructor.
3. The game board will be displayed in the UIAxes component.
4. Use the `Choose Fate` dropdown menu to select "Player 1" or "Player 2."
5. Click on an empty position on the board to make a move.
6. Alternate turns with the other player until one player wins or the game ends in a draw.
7. The game will display a message indicating the winner or a draw.

## Customization

You can customize the appearance and behavior of this Tic-Tac-Toe game app by modifying the MATLAB code within the class definition. You can add features such as checking for a win, implementing a reset button, or creating a scoring system.

## License

This MATLAB app is provided without a specific license. It is intended for educational and recreational purposes. You are welcome to use, modify, and distribute it for non-commercial purposes.

## Contact

If you have any questions or need further assistance with this MATLAB app, please feel free to contact the author, [Your Name], at [your@email.com].
