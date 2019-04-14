# Scoring:
![points](https://user-images.githubusercontent.com/9196372/56091917-05225500-5ead-11e9-88f8-c1ce21b60ced.png)

# Bot rules:
 - Only do stuff between `get_move` being called and you returning an action - no calculating on someone else's turn
 - Do whatever you want about parallelizing it, spawning subprocesses, calling external libraries
 - Return a move within the time limit or a random move will be made

# TODO:
 - Currently expanding the game tree involves a deep copy of the whole gameBoard. This can be vastly improved with a simpler game state.
 - Trivial MCTS bot doesn't work, no idea why.
