
# Hangman Solver

## Description
The Hangman Solver is a Java-based application designed to assist users in solving Hangman games. By narrowing down the possible words from a dictionary based on user inputs, the solver intelligently suggests the most probable letter to guess next. It's a fun tool to enhance your Hangman game experience, offering a strategic edge in guessing words correctly.

## Features
- **Intelligent Letter Guessing**: Suggests the most probable letter to guess next based on the current state of the game.
- **Dynamic Dictionary Filtering**: Narrows down possible words from the dictionary as the game progresses.
- **Game Progress Display**: Shows the current guessed word, past guesses, and possible word list as the game unfolds.

## How to Run
1. **Prerequisites**: Ensure you have Java installed on your machine.
2. **Clone the Repository**:
   ```bash
   git clone https://github.com/tianhg28/hangman-solver
   cd hangman-solver
   ```
3. **Run the Application**:
   ```bash
   java HangmanMain
   ```
4. **Follow the on-screen prompts** to input the number of letters in the word and respond to the solver's guesses.

## Usage
1. Start the game, and the solver will ask for the number of letters in the word.
2. The solver suggests the best letter to guess. Input 'y' (yes) or 'n' (no) based on whether the guess was correct.
3. If correct, provide the position(s) of the letter in the word.
4. Continue until the solver guesses the word or the word is revealed.

## Components
- **HangmanMain**: The main class that runs the game, interacts with the user, and integrates the solver.
- **HangmanSolver**: The core class that contains the logic for suggesting letters and filtering the dictionary based on guesses.

## Contributing
Contributions to improve the Hangman Solver are welcome. Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT license. Please see the LICENSE.md file for more details.
