# Python Slot Machine Game

A simple command-line slot machine game built with Python. Players can deposit money, place bets on up to three lines, spin the slot machine, and win payouts based on matching symbols.

## Features

* Deposit an initial balance
* Bet on 1 to 3 lines
* Choose a bet amount per line
* Random slot machine spins
* Different symbol frequencies for realistic odds
* Symbol-based payout system
* Tracks winning lines
* Updates player balance after each spin
* Input validation for a smooth user experience

## Symbol Payouts

| Symbol | Payout Multiplier |
| ------ | ----------------: |
| A      |                5× |
| B      |                4× |
| C      |                3× |
| D      |                2× |

## Symbol Frequency

Symbols are not equally likely to appear.

| Symbol | Count |
| ------ | ----: |
| A      |     2 |
| B      |     4 |
| C      |     6 |
| D      |     8 |

A lower count means the symbol is rarer, while a higher count makes it more likely to appear.

## How to Run

1. Make sure Python 3 is installed.
2. Clone the repository.

```bash
git clone https://github.com/Student-boy143/Slot-Machine.git
```

3. Navigate to the project folder.

```bash
cd Slot-Machine
```

4. Run the game.

```bash
python main.py
```

## Example Gameplay

```text
How much would you like to deposit? $100
Current balance is $100.

How many lines would you like to bet on (1-3)? 3
How much would you like to bet on each line? $10

You are betting $10 on 3 lines. Total bet is $30.

A | B | C
A | B | C
A | B | D

You won $50
Winning lines: 1

Current balance is $120
```

## Concepts Practiced

* Functions
* Lists and dictionaries
* Nested loops
* Input validation
* Random module
* Returning multiple values
* `for...else` statements
* Basic game logic
* Command-line applications

## License

This project is intended for learning and practice purposes.
