# PIG Game

PIG is a simple dice game where players take turns rolling a six-sided die to accumulate points. The first player to reach a specified score wins.

## How to Play

1. Run the Python script `pig_game.py`.
2. Enter the number of players (2 - 4).
3. Players take turns rolling a die.
4. Each turn, a player can roll the die multiple times to accumulate points.
5. If a player rolls a 1, they lose all points accumulated in that turn, and it becomes the next player's turn.
6. The game continues until one player reaches or exceeds the maximum score.

## Rules

- Each player's turn consists of repeatedly rolling a die:
  - If the player rolls a 1, they lose all points accumulated in that turn, and it's the next player's turn.
  - If the player rolls a number other than 1, the number is added to their turn total.
  - The player can choose to hold, which adds the turn total to their total score, and it's the next player's turn.

## Requirements

- Python 3.x

## How to Run

1. Clone this repository or download the `pig_game.py` file.
2. Open a terminal or command prompt.
3. Navigate to the directory where `pig_game.py` is located.
4. Run the following command:
   ```
   python pig_game.py
   ```

## Sample Gameplay

```
Enter the number of players (2 - 4): 3

Player number 1 turn has just started!
Your total score is: 0 

Would you like to roll (y)? y
You rolled a: 4
Your score is: 4
Would you like to roll (y)? y
You rolled a: 3
Your score is: 7
Would you like to roll (y)? y
You rolled a: 2
Your score is: 9
Would you like to roll (y)? y
You rolled a: 6
Your score is: 15
Would you like to roll (y)? y
You rolled a: 1
You rolled a 1! Turn done!
Your total score is: 0

...

Player number 2 turn has just started!
Your total score is: 20 

Would you like to roll (y)? y
You rolled a: 2
Your score is: 2
Would you like to roll (y)? y
You rolled a: 1
You rolled a 1! Turn done!
Your total score is: 20

Player number 3 turn has just started!
Your total score is: 25 

Would you like to roll (y)? y
You rolled a: 4
Your score is: 4
Would you like to roll (y)? y
You rolled a: 5
Your score is: 9
Would you like to roll (y)? n
Your total score is: 34

...

Player number 2 is the winner with a score of: 55

```

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).