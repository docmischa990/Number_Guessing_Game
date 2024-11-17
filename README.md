# Number Guessing Game

This is a Python-based number guessing game where the user must guess a randomly generated number within a specified range. The game provides feedback on whether the guess is too high or too low, and allows the user to set the range and number of attempts.


### Features:
- **Customizable range**: You can define the minimum and maximum number for the guessing range.
- **Maximum attempts**: Set the maximum number of guesses allowed.
- **Best score tracking**: The game keeps track of your best score (fewest attempts to guess correctly).
- **Play again**: After finishing a game, you can choose to play again or quit.


### How to Play:
1. The game will ask you to specify the minimum and maximum values for the number range.
2. Then, you will be prompted to enter your guess.
3. If your guess is too high or too low, the game will let you know.
4. If you guess correctly, the game will display the number of attempts it took and check if it's your best score.
5. You can continue playing or quit after each game.


### Example Gameplay:

```bash
Enter the minimum value for the guessing range: 1
Enter the maximum value for the guessing range: 100
Enter the maximum number of attempts you want to allow: 5

Guess the number between 1 and 100: 50
Too low!

Guess the number between 1 and 100: 75
Too high!

Guess the number between 1 and 100: 60
Congratulations! You guessed the number in 3 attempts.
New best score: 3 attempts!

Do you want to play again? (y/n): n
Thanks for playing! Your best score was 3 attempts. Goodbye.
```


### Requirements:
Python 3.x or above


### How to Run:
- Clone the repository to your local machine.
- Navigate to the folder where the Python file is located.
- Run the script:
  python number_guessing_game.py


  Enjoy playing and may you achieve the best score possible!



### Key Points:
- This README describes how the game functions, with features like customizable ranges, attempt limits, and tracking the best score.
- It includes a sample gameplay session, showing how to interact with the game.
- The game’s requirements and how to run it are also included for ease of setup.

Let me know if you need any further customizations or additions!
