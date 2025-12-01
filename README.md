## Features
-> Random number generation (1 to 100)
-> Helpful hints:
-> Too Low
-> Too High
-> High Score System
-> Saves the best score in highscore.txt
-> Loads the score each time the game starts
-> Validates user input (no crashes on invalid entries)
-> Graceful exit if the user presses Ctrl + C
-> Automatic handling of missing or invalid high-score files
-> File Used
-> highscore.txt
-> Stores the fewest number of guesses achieved.

If the file doesn’t exist or contains invalid text, the program resets the high score automatically.

## How the Game Works

-> The program picks a secret number between 1 and 100.
-> You guess a number.
* The game responds with:
* ⬆️ Too Low
* ⬇️ Too High
* Correct!
* When you win, the game shows how many guesses you used.

## Purpose of the Project

This project is ideal for learning:
 * File handling
 * Input validation
 * Random number generation
 * Control structures (if, loops, exceptions)
  * Basic game logic
