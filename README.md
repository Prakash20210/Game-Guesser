# Project Name
# Game-Guesser

# Project Overview

This Java program is a simple number guessing game involving a Guesser and three Players, with an Umpire deciding the winner(s). Here's how the game works:

The Guesser class represents the Guesser who has to guess a number.
The Player class represents the Players who have to guess a number.
The Umpire class acts as the mediator to collect guesses from the Guesser and the three Players and decide the winner(s).
The GameGuesser class is the main class to run the game.

# Features
1.The Guesser enters their guessed number.

2.Three Players enter their guessed numbers.

3.The Umpire compares the Guesser's number with the numbers guessed by the Players and announces the winner(s) or if the game is tied.


# Explanation 
1=> Guesser class:
guessNumber(): Takes the Guesser's input from the console as an integer and returns it.

2=> Player class:
guessNumber(): Takes each Player's input from the console as an integer and returns it.

3=>Umpire class:

~ collectNumFromGuesser(): Creates a Guesser object, collects the Guesser's guessed number using the guessNumber() method, and stores it in the numFromGuesser variable.

~ collectNumFromPlayer(): Creates three Player objects, collects guessed numbers from each Player using the guessNumber() method, and stores them in numFromPlayer1, numFromPlayer2, and numFromPlayer3 variables.

~ compare(): Compares the Guesser's guessed number with the numbers guessed by the Players and announces the winner(s) or if the game is tied.

4=> GameGuesser class:

~ main(): The entry point of the program. It creates an Umpire object, collects inputs from the Guesser and Players, and then compares the guesses to determine the winner(s) or if the game is tied.


# Contributing
Contributions to the Gane-Guesser are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/your_feature
Commit your changes: git commit -m "Add your feature"
Push the branch to your fork: git push origin feature/your_feature
Submit a pull request to the develop branch.

# License
The Guesser-Game is released under the MIT License..]

# Contact
For any questions or feedback, feel free to reach out to us at prakashg281@gmail.com
