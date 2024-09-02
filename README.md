Number Guessing Game
This Python script implements a classic number guessing game. The user is tasked with guessing a randomly generated number within a specified range. The script provides hints to guide the player towards the correct solution.

How it Works:

Random Number Generation: A random integer between 1 and 100 is generated using the random module.
User Input: The user is prompted to enter their guess.
Input Validation: The script checks if the input is within the valid range (1-100). If not, an error message is displayed, and the user is asked to try again.
Guess Comparison: The user's guess is compared to the randomly generated number.
If the guess is correct, the game ends with a congratulatory message and the number of attempts taken.
If the guess is incorrect, the script provides hints to help the user narrow down the possibilities.
Game Loop: The process of guessing and receiving feedback continues until the user guesses the correct number or chooses to quit.
Features:

Random Number Generation: Ensures a different number each time the game is played.
Input Validation: Prevents invalid guesses and provides informative error messages.
Hints: Offers helpful clues to guide the user towards the correct answer.
Attempt Counting: Keeps track of the number of attempts made, encouraging players to try to solve the puzzle in as few guesses as possible.
User-Friendly Interface: Provides a clear and concise interface for the user to interact with the game.
Example Gameplay:

-------------------------
I'm thinking of a number between 1 and 100. Can you guess it?
-------------------------
50
-------------------------
You're getting closer, but your guess is still high.
-------------------------
30
-------------------------
Getting closer and closer... Think bigger.
-------------------------
40
-------------------------
Congrats you guessed it correctly!!
Attempts = 3
Thanks for playing
-------------------------
This simple yet engaging game provides a fun and challenging way to test your problem-solving skills and improve your logical thinking.
