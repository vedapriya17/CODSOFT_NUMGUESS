# guessingnum_codsoft
## Number Guessing Game in Java
* Introduction
Welcome to the Number Guessing Game! This Java console application provides an engaging experience where players can guess a randomly generated number within a predefined range. The game includes features such as hints, timing records, scoring, and a give-up option for revealing the answer.
## Features
* Hints
After each guess, the game provides helpful hints to guide players towards the correct answer. If the guess is too high, the game will suggest "Lower," and if the guess is too low, the hint will be "Higher."

* Timing Records
The game records the time it takes for players to successfully guess the correct number. This adds a competitive element and encourages players to improve their time with each attempt.

* Scoring
Players earn a score based on the time taken to guess the number. The faster the correct guess, the higher the score. A scoring algorithm is in place to calculate and display the player's score at the end of each game.

* Give Up Option
If a player is stuck or wants to end the game prematurely, they can use the "give up" option. This option reveals the correct answer and concludes the game, providing an opportunity for players to learn and improve.

## How to Play
* Enter your name to begin the game.
* The game will generate a random number within a predefined range.
* Guess the number by entering your choice.
* Receive hints after each guess.
* Continue guessing until you find the correct number.
## Controls
* Enter your guess when prompted.
* Type 'give up' to reveal the correct answer and end the game.
Follow on-screen instructions to navigate through the game.

## Code Snippets
* Random Number Generation
  // Generate a random number within the specified range
int secretNumber = generateRandomNumber(minRange, maxRange);

* Providing Hints
  // Check if the guess is correct and provide hints
String hint = provideHint(userGuess, secretNumber);

* Recording Timing and Calculating Score
  // Record timing
long endTime = System.currentTimeMillis();
long elapsedTime = endTime - startTime;

// Calculate score
int score = calculateScore(elapsedTime);

* Give Up Option
  // Give up option
if (userInput.equalsIgnoreCase("give up")) {
    revealAnswer(secretNumber);
    endGame();
}

Acknowledgments
* Inspired by classic number guessing games.
* Built with Java and love for coding!
* Feel free to contribute to the project or customize it to suit your preferences. Enjoy the game!

