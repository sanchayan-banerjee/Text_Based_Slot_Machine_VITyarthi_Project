# **Project Report On Text-Based Slot Machine Game**

## **Introduction**
Slot machines are probability-based gambling machines commonly seen in casinos. This project aims to simulate a simple slot machine in a Python terminal environment.The user can deposit money, place their bets, spin the slot machine and earn winnings based on matching symbol combinations.

## Project demonstrates the following things:-
- Randomness.
- Modular Programming.
- Input Validation.
- Game-Loop Design.
- Balance Management.
- Payout Computation.


## **Problem Statement**
- To design and implement a text-based slot machine game in Python that allows users to deposit money, place bets, spin a randomized slot board, and receive payouts based on matching symbols across selected betting lines.The project focuses on user input handling, balance management, randomization, modular logic structure, and reward calculation.


## **Project Objectives**
- Allow players to deposit money.
- Enable betting on multiple lines.
- Generate slot results using randomness.
- Compute winnings based on symbol matches.
- Update player's balance simultaneouly.
- Allow continuous play until player exits.


## **Tools and Technologies Used While Making this Project**
| Category | Selection |
|----------|-----------|
| Programming Language | Python 3 |
| Libraries Used | random (built-in) |
| IDE | Visual Studio Code |
| OS | Windows 10 |
| Version Control | Git + GitHub |

- No external libraries were installed for making this project.


## **Approach and Methodology in Top-Down View**
-  Player deposits money.
-  Player selects number of lines to bet on.
-  Player selects bet amount.
-  Slot machine generates random symbols.
-  Program checks for winning rows.
-  Balance is updated.
-  User decides to continue or exit.


## **System Flow in Top-Down View**
- Step 1: Start Program.
- Step 2: User Deposits Balance.
- Step 3: User Selects Betting Lines.
- Step 4: User Sets Bet Amount.
- Step 5: Random Slot Generation.
- Step 6: Evaluate Winning Lines.
- Step 7: Add or Subtract Balance.
- Step 8: User Chooses to Continue or Exit.


## **Implementation Details** 

### Core Components:-
- Deposit function.
- Betting validation.
- Weighted random generator.
- Slot display formatter.
- Winning checker.
- Balance handler.
- Main gameplay loop.

### Symbol logic:-
- A: Rare in terms of frequency, high payout.
- D: Common in terms of frequency, low payout.


## **Project Structure**
- **main.py**: Contains the complete slot machine program.
- **README.md**: Contains documentation and instructions.
- **images/output1.png**: Output screenshot.


## **Results and Observations**
### Expected Program Behaviour:-
- Balance decreases gradually over many spins.
- Randomness affects winnings.
- Rare symbols give more rewards.

### Observations:-
- Winnings are intermittent to mimic how real slot machines behave.


## **Analysis**
### Effects of Parameters:-
| Parameter | Impact |
|----------|--------|
| Symbol rarity | It determines reward frequency. |
| Bet size | It affects risk and payout. |
| Number of lines | It affects total cost. |
| Randomness | It maintains unpredictability. |

### Inference Drawn :-
- The game behaves statistically close to real slot machines where player loses gradually over time but occasionally wins.


## **The Challenges I faced while doing this Project** 
They are as mentioned below:-
- Preventing invalid user inputs.
- Avoiding bets greater than balance.
- Ensuring readable output formatting.
- Designing 'betting logic', safely.


## **My Learnings**
They are as mentioned below:-
- I learnt about planning modular code.
- I came to know about CLI game development.
- Randomization logic.
- I learnt about safe user input handling.
- Balance tracking mechanics.
- Probability-driven design.


## **The Possible Future Enhancements in This Project**
- GUI Version.
- Sounds and Effects.
- Player-history Records.
- Saved Sessions.
- Progressive Jackpots.
- An Analytics System.


## **Conclusion**
In this project I successfully implemented a functional "Text Based Slot Machine" simulation using Python.It fulfills all intended objectives, provides an interactive experience and reflects a real slot-machine behaviour through calculated randomness and payout rules.


## **References**
### For furthur references check out the following:-
- Python Official Documentation: 'random' module
- Research on Casino Slot Payout Patterns.



