# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

The most difficult part of tic-tac-toe was definitely the has_won method. Figuring out how to check the test cases in a more pythonic way instead of brute forcing it fascinated me. I liked how we used splicing through indexes with the colons in order to account for every possible case. 

2. Explain how you would add a computer player to the game.

To add a computer player to the game, I would write a function that generates a move for a random spot, according to where the human-player made their move.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

I would figure out a way to have a function that checks for the best possible move for the player. For example, if the human player made their first move in the corner, the function could check that the middle square results in the most combinations that would allow the human player to win. Therefore, the AI would place their move there in order to restrict the human player from making that move.