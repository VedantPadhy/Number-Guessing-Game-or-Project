# Number-Guessing-Game-or-Project
 with Basic Python

## Introduction
This is a simple number guessing game implemented in Python. The computer randomly selects a number between 1 and 100, and the player has to guess the number. The game provides hints to the player whether their guess is too high or too low. The game continues until the player guesses the number correctly.

## How to Play
1. Run the Python script.
2. The script will prompt you to guess a number between 1 and 100.
3. Enter your guess and press Enter.
4. The script will provide hints if your guess is too high or too low.
5. Continue guessing until you correctly identify the number.
6. The script will display the total number of attempts you made to guess the number correctly.

## Code
import random

n = random.randint(1, 100)
a = -1
guesses = 0

while a != n:
    a = int(input("Guess a number: "))
    if a > n:
        print("Lower number please")
        guesses += 1
    elif a < n:
        print("Higher number please")
        guesses += 1

print(f"You have guessed the number {n} correctly in {guesses} attempts")
Example Output
Guess a number: 50
Higher number please
Guess a number: 75
Lower number please
Guess a number: 63
Higher number please
Guess a number: 70
Lower number please
Guess a number: 67
Higher number please
Guess a number: 68
Lower number please
Guess a number: 65
You have guessed the number 65 correctly in 8 attempts
Requirements
Python 3.x

Running the Game
Make sure you have Python 3.x installed on your system.

Copy the code provided above into a Python file (e.g., number_guessing_game.py).

Open your terminal or command prompt.

Navigate to the directory where the Python file is saved.

Run the Python file using the command: python number_guessing_game.py

Enjoy the game and happy guessing!


Feel free to customize this README file further as per your needs. If you need any additional information or modifications, just let me know!

