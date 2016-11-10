# ConnectFourGame
Connect Four as a Web API

Connect Four is a two-player connection game in which the players first choose a color and then take

turns dropping colored discs from the top into a seven-column, six-row vertically suspended grid. The

pieces fall straight down, occupying the next available space within the column. The objective of the

game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

Your mission is to implement the Connect Four game as a Web API with a computer opponent.

### Project Description

Connect Four Web API should supports the following actions:

1. Start a new game – the API should allow the user to start a new game.

  a. Request Requirements

    i. The player will be able to choose whether they want to play first or second i.e., disc color.

  b. Response Requirements

    i. A unique id for the game which will be used in subsequent API calls.

    ii. The state of the game board (i.e. position of every played disc on the gameboard). If the player has elected to go second, the game board should show the first move made by the computer player.

2. Single Player/Opponent Turn – the user will be able to play a move and in response see the resulting move of the computer opponent.

  a. Request Requirements

    i. The player should be able to indicate where on the gameboard they would like to play their disc.

  b. Response Requirements

    i. The state of the game board (i.e. position of every played disc on the gameboard) after the player has made their move. The state should include the resulting move of computer opponent.

  ii. The position on the gameboard where the computer opponent has placed their colored disc.

### Error Handling

All API calls have adequate error handling.

### Data Persistence

All data maintained by the app is ephemeral i.e.,  all data stored by app is restarted

the application clears any data stored in memory by the app.
