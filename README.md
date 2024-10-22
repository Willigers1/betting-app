# Slot Machine Game - README

## Overview
This is a simple terminal-based slot machine game written in Python. Players can deposit money, choose the number of lines to bet on, and place bets for each line. The game simulates the spinning of a slot machine with three rows and three columns, using randomly selected symbols. Players can win based on matching symbols across the lines they bet on, and the payout is determined by the symbol values.

## Features
- Deposit funds to play the game.
- Place bets on up to 3 lines.
- Simulate a slot machine spin with symbols that have different values.
- Calculate winnings based on the symbol and the amount bet.
- Display the current balance after each spin.
- The game continues until the player decides to quit or runs out of balance.

## Symbols and Their Values
The game uses four symbols with varying frequencies and payouts:
- **Symbol A**: Appears 2 times, Payout = 5x the bet.
- **Symbol B**: Appears 4 times, Payout = 4x the bet.
- **Symbol C**: Appears 6 times, Payout = 2x the bet.
- **Symbol D**: Appears 8 times, Payout = 3x the bet.

## Project Structure
- **`symbol_count`**: Defines how frequently each symbol appears in the slot machine spin.
- **`symbol_value`**: Defines the payout values for each symbol.
- **Functions**:
  - `deposit()`: Prompts the player to deposit money into the game.
  - `get_number_of_lines()`: Asks the player how many lines they want to bet on.
  - `get_bet()`: Prompts the player to place a bet on each line.
  - `get_slot_machine_spin()`: Simulates the slot machine spin by randomly selecting symbols for each column.
  - `print_slot_machine()`: Displays the slot machine's current state after a spin.
  - `check_winnings()`: Checks if the player has won on any of the lines they bet on and calculates the total winnings.
  - `game()`: Manages a single round of the game, including betting, spinning the slot machine, and updating the balance.
  - `main()`: The entry point of the game that manages the player’s balance and handles multiple rounds.

## How to Play
1. **Deposit**: The game will prompt you to deposit money to start playing.
2. **Choose Lines**: Select how many lines (1 to 3) you want to bet on.
3. **Place Bet**: Enter how much you want to bet on each line (between 1 and 100).
4. **Spin**: After confirming your total bet, the slot machine will spin, and the results will be displayed.
5. **Check Winnings**: If you match symbols on any of the lines, you will be rewarded based on the symbol values.
6. **Continue or Quit**: After each round, you can either continue playing or quit the game.

## Installation and Setup
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/slot-machine-game.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd slot-machine-game
    ```
3. **Run the game**:
    ```bash
    python slot_machine_game.py
    ```

## Requirements
- Python 3.x

## Future Enhancements
- Add more symbols for increased complexity.
- Implement a graphical user interface (GUI) to replace the terminal interface.
- Add additional betting features and bonus rounds.

## License
This project is open-source and available under the MIT License.

---

Enjoy playing the Slot Machine Game!
