This is a game package built to practice OOP concept in python and package submission to pypi.

The game consists of 2 players, one of them picking a number within a specific range and the other one guessing the number. The game ends by guessing the chosen number and opens a new game session directly. 


Currently, the package needs a fix as in order to play now, one has to go through the following process:
```
from oop_guessing_game.oop_guessing_game import ComputerPlayer, PersonPlayer, Game


player1 = ComputerPlayer()
player2 = PersonPlayer(name='me')
gamesko = Game(players=[player1, player2], max_number={max_number})
gamesko.play_game()
```
