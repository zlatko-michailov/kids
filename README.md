# Kids Repository
Copyright (c) Zlatko Michailov

This repository contains fun projects that teach kids how to program.

Each project is implemented using __JavaScript__ contained in a single HTML page.

The UI is quite edgy.
The focus has been on the _code_, not on the UI.

Feel free to suggest other simple and fun projects by filing issues. 



## Basic Level
These projects require knowledge on variables, functions, conditions, loops, and arrays.

### CodeBreaker.Sole
(__Coming soon.__)

This project implements a simplified version of the popular paper-and-pencil game 
[Bulls and Cows](https://en.wikipedia.org/wiki/Bulls_and_Cows).

Game limitations:
- The user is the sole code breaker. The computer is only a code maker.



## Intermediate level
These projects involve _nesting_ of the basic programming elements - 
conditions, loops, and function calls. 

### TicTacToe.Weak
[__Try it now.__](TicTacToe.Weak/TicTacToe.Weak.html)

This project implements the popular paper-and-pencil game
[Tic Tac Toe](https://en.wikipedia.org/wiki/Tic-tac-toe).

Game limitations: 
- The user always has the first move.
- The user always uses the "X" symbol.

As the name suggests, this program implements a weak algorithm -
it picks the first available cell probing the center first, then the corners,
and lastly the middles.
This weak algorithm was favored for its simplicity over the more complex 
_minimax_ algorithm which is implemented by [TicTacToe.Strong](#TicTacToe.Strong).
 


## Advanced Level 
These projects use _recursion_.

### TicTacToe.Strong
(__Coming soon.__)

This project implements the same game that [TicTacToe.Weak](#TicTacToe.Weak) does with the same limitations. 
The difference is that this project uses a recursive, _minimax_, algorithm to chose the best move.



## Pro Level
These projects involve complex logic.

### CodeBreaker.Compete
(__Coming later.__)

This project implements the same game that [CodeBreaker.Sole](#CodeBreaker.Sole) does with the same limitations. 
The difference is that the game is in _competition_ mode - the computer makes moves against the user.
