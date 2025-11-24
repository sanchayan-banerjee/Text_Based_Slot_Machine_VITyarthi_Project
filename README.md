Text-Based Slot Machine

1. **Problem Statement:-** 
To design and implement a text-based slot machine game in Python that allows users to deposit money, place bets, spin a randomized slot board, and receive payouts based on matching symbols across selected betting lines.The project focuses on user input handling, balance management, randomization, modular logic structure, and reward calculation.

2. **Objectives:-**
a) Simulate a simplified casino slot machine using Python.
b) Allow interactive user participation (deposit, betting, spinning).
c) Generate random slot results based on symbol rarity.
d) Calculate winnings based on symbol payout values.
e) Maintain the player’s account balance throughout the game.

3. **Project Summary:-**
This program lets the user:
a) Deposit money.
b) Select how many lines they want to bet on.
c) Choose a bet amount per line.
d) Spin the machine.
e) View the result grid.
f) Check winnings.
g) Continue or quit.
h) The system then updates the balance accordingly.

4. **System Flow (Top-Down View):-**
Step 1: Start Program.
Step 2: User Deposits Balance.
Step 3: User Selects Betting Lines.
Step 4: User Sets Bet Amount.
Step 5: Random Slot Generation.
Step 6: Evaluate Winning Lines.
Step 7: Add or Subtract Balance.
Step 8: User Chooses to Continue or Exit.

5. **Project Structure:-**
-**main.py**: Contains the complete slot machine program.
-**README.md**: Contains documentation and instructions.
-**images/output1.png**: Output screenshot.

6. **Requirements:-**
-Python 3.x .
-No external libraries needed.

7. **How to Run the Program:-**
Open terminal and enter:
 python slot_machine.py
Or,
 python3 slot_machine.py

8. **Game Rules:-**
a) Minimum bet: $1.
b) Maximum bet: $100.
c) You may bet on 1 – 3 lines.
d) Total betting cost = bet per line × number of lines.
e) If all symbols match across a bet line → you win based on value.

9. **Symbol Mechanics:-**
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

10. **Sample Output Screenshot:-**
![Output Screenshot](images/output1.png)

11. **Implementation Approach (Top-Down):-**
High-Level Components are as follows:
a) Main Game Loop.
b) Deposit handler.
c) Betting and validation.
d) Random slot reel generator.
e) Display function.
f) Winnings evaluator.
g) Balance updater.

Design Method Used is as follows:
a) Modular design.
b) Function-based organization.
c) Input validation.
d) Probability-based random draws.

12. **Concepts Used:-**
a) **Functions.**
b) **Dictionaries.**
c) **Loops.**
d) **Random module.**
e) **String formatting.**
f) **Conditional logic.**
g) **Array indexing.**
h) **Data validation.**

13. **Optional Future Enhancements:-**
a) GUI version.
b) Leaderboard system.
c) API-based payout tracking.
d) Color-based terminal UI.

14. **Project By:**
**Sanchayan Banerjee**
**GitHub:sanchayan-banerjee**



