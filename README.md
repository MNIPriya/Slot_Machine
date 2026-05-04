🎰 Slot Machine Game (Python)

This is a simple command-line based Slot Machine game built using Python. The program simulates a real slot machine where users can deposit money, place bets on multiple lines, and spin to try their luck.

🚀 Features
User can deposit money to start playing
Option to bet on 1 to 3 lines
Adjustable bet amount per line
Randomized slot spinning using Python’s random module
Winning system based on matching symbols across rows
Displays winning lines and total winnings
Continuous gameplay until the user quits
🧠 How It Works
The slot machine consists of a 3x3 grid (3 rows × 3 columns).
Each symbol (A, B, C, D) has:
A frequency (how often it appears)
A value (how much it pays)
When the user spins:
Random symbols are generated for each column
The program checks if all symbols in a selected row match
If they match, the user wins based on the symbol value and bet
🎲 Symbol Details
Symbol	Count	Value
A	2	5x
B	4	4x
C	6	3x
D	8	2x
Higher value symbols are rarer, making the game balanced and interesting.
📌 Game Flow
User deposits money
Chooses number of lines to bet on
Sets bet amount per line
Spins the slot machine
Wins are calculated and added/subtracted from balance
Game continues until the user quits
🛠️ Technologies Used
Python (Core concepts)
Random module for simulation
Loops, functions, and input validation
💡 Learning Outcomes
Understanding of Python functions and loops
Use of dictionaries for game logic
Handling user input and validation
Building a simple game logic system
