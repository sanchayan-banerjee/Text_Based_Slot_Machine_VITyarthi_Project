## **Text-Based Slot Machine**

## **Problem Statement:-** 
To design and implement a text-based slot machine game in Python that allows users to deposit money, place bets, spin a randomized slot board, and receive payouts based on matching symbols across selected betting lines.The project focuses on user input handling, balance management, randomization, modular logic structure, and reward calculation.

## **Objectives:-**
- Simulate a simplified casino slot machine using Python.
- Allow interactive user participation (deposit, betting, spinning).
- Generate random slot results based on symbol rarity.
- Calculate winnings based on symbol payout values.
- Maintain the player’s account balance throughout the game.

## **Project Summary:-**
This program lets the user:
- Deposit money.
- Select how many lines they want to bet on.
- Choose a bet amount per line.
- Spin the machine.
- View the result grid.
- Check winnings.
- Continue or quit.
- The system then updates the balance accordingly.

## **System Flow in Top-Down View:-**
- Step 1: Start Program.
- Step 2: User Deposits Balance.
- Step 3: User Selects Betting Lines.
- Step 4: User Sets Bet Amount.
- Step 5: Random Slot Generation.
- Step 6: Evaluate Winning Lines.
- Step 7: Add or Subtract Balance.
- Step 8: User Chooses to Continue or Exit.

## **Project Structure:-**
- **main.py**: Contains the complete slot machine program.
- **README.md**: Contains documentation and instructions.
- **images/output1.png**: Output screenshot.

## **Requirements:-**
- Python 3.x .
- No external libraries needed.

## **How to Run the Program:-**
- Open terminal and enter:
 python slot_machine.py
- Or,
 python3 slot_machine.py

## **Game Rules:-**
- Minimum bet: $1.
- Maximum bet: $100.
- You may bet on 1 – 3 lines.
- Total betting cost = bet per line × number of lines.
- If all symbols match across a bet line → you win based on value.

## **Symbol Mechanics:-**
Symbol Frequency(Rarity)
| Symbol | Count |
| ------ | ----- |
| A      | 2     |
| B      | 4     |
| C      | 6     |
| D      | 8     |
Smaller count signifies higher rarity.

Payout Multipliers
| Symbol | Pays   |
| ------ | ------ |
| A      | 5× bet |
| B      | 4× bet |
| C      | 3× bet |
| D      | 2× bet |

## **Sample Output Screenshot:-**
 [Sample Output Screenshot](screenshots/output1.png)

## **Implementation in Top Down Approach :-**
High-Level Components are as follows:
- Main Game Loop.
- Deposit handler.
- Betting and validation.
- Random slot reel generator.
- Display function.
- Winnings evaluator.
- Balance updater.

Design Method Used is as follows:
- Modular design.
- Function-based organization.
- Input validation.
- Probability-based random draws.

## **Concepts Used:-**
- **Functions.**
- **Dictionaries.**
- **Loops.**
- **Random module.**
- **String formatting.**
- **Conditional logic.**
- **Array indexing.**
- **Data validation.**

## **Optional Future Enhancements:-**
- GUI version.
- Leaderboard system.
- API-based payout tracking.
- Color-based terminal UI.

## **Project By:**
- **Sanchayan Banerjee**
- **GitHub:sanchayan-banerjee**



