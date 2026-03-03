
**Number Guessing Game – Description**

This program is a simple Number Guessing Game where the computer randomly selects a number between 1 and 100, and the user must guess it correctly.

First, the program asks the user whether they want to start the game. If the user enters "yes", the game continues; otherwise, it exits. The game rules are stored in a tuple and displayed using a loop.

The program then imports the random module and generates a secret number between 1 and 100. A while loop is used to repeatedly ask the user to enter their guess.

For each guess:

If the guess is lower than the secret number, the program displays "Too Low".

If the guess is higher than the secret number, it displays "Too High".

If the guess matches the secret number, the user wins and the game ends.

The program keeps track of:

The total number of attempts

All guesses made by the user (stored in a list)

After the game ends, the results are stored in a dictionary and displayed as a game summary, showing the secret number, total attempts, and the list of guesses.

This program demonstrates the use of loops, conditional statements, tuples, lists, dictionaries, and random number generation in Python.
