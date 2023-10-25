# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
    The most difficult part was checking who won. My first solution (using lists) didn't work out, and my current solution
    feel horribly inefficient.

2. Explain how you would add a computer player to the game.
    A computer player would be added by placing pieces automatically according to the current state of the board, after the human player
    has played.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
    Since tic-tac-toe is a game with one optimal move in all situations, I would think that having a tree of decisions that use the
    state of the board to play the known best move in that situation would work. Inmy mind, the computer player doesn't need to learn how to play because the situations its playing in are so simple.