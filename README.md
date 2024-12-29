# Guessing Game

This is a basic Rust CLI program that uses dependencies to let a person guess a random number between 1 and 100. The program will keep track of the number of guesses and provide feedback on whether the guess is too high or too low.

## Features

- Generates a random number between 1 and 100.
- Prompts the user to input their guess.
- Provides feedback if the guess is too high or too low.
- Tracks the number of guesses.
- Displays the total number of guesses when the user wins.

## Dependencies

- `rand` crate for generating random numbers.

## Setup

1. Ensure you have Rust installed. If not, you can install it from [here](https://www.rust-lang.org/tools/install).
2. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/guessingGame.git
    ```
3. Navigate to the project directory:
    ```sh
    cd guessingGame/guessing_game
    ```
4. Build the project:
    ```sh
    cargo build
    ```
5. Run the project:
    ```sh
    cargo run
    ```

## Usage

1. The program will prompt you to guess a number between 1 and 100.
2. Input your guess and press Enter.
3. The program will provide feedback if your guess is too high or too low.
4. Continue guessing until you find the correct number.
5. The program will display the total number of guesses when you win.

## Example

```
Guess the number!
Please input your guess.
50
You guessed: 50
Too small!
Please input your guess.
75
You guessed: 75
Too big!
Please input your guess.
63
You guessed: 63
You win! It took you 3 guesses.
```

## License

This project is licensed under the MIT License.
