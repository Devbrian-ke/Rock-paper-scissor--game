
Rock Paper Scissors Game
Python 3  |  CLI Game  |  Open Source  |  Beginner Friendly


  About The Project:
Rock Paper Scissors is a classic command-line game built in Python where you compete against the computer. The computer randomly selects its move, and the program determines the winner based on the traditional rules of the game. It's a fun, lightweight project that demonstrates core Python programming concepts including functions, loops, conditionals, and the random module.
Features:
•Play unlimited rounds in a continuous loop until you choose to quit
•The computer randomly selects rock, paper, or scissors each round
•Instant win/loss/tie detection and feedback after every round
•Input validation — invalid entries are caught and the player is prompted to try again
•Clean exit by typing 'quit' at any time

 How It Works
The game follows a simple flow:
1.  The player is prompted to enter rock, paper, or scissors (or 'quit' to exit).
2.  The input is validated — if invalid, the player is asked to try again.
3.  The computer randomly picks its choice using random.choice().
4.  The get_winner() function compares both choices and returns the result.
5.  The result is printed and the loop continues for the next round.

 Win Conditions:
The following table summarizes how winners are determined:
Player Choice	Computer Choice	Result
Rock	Scissors	You Win! 
Paper	Rock	You Win! 
Scissors	Paper	You Win! 
Rock	Rock	It's a Tie! 
Rock	Paper	Computer Wins! 

  Getting Started:
Prerequisites
Make sure you have Python 3 installed on your machine.
Installation & Running
Clone the repository:
    git clone https://github.com/Brisoft-ke/Rock-paper-scissor--game.git
Navigate to the project directory:
    cd Rock-paper-scissor--game
Run the game:
    python rock-paper-scissor game.py

  Project Structure:
Rock-paper-scissor--game/

├── rock-paper-scissor game.py    # Main game file
└── README.md                     # Project documentation

 Author:
Brisoft-ke  —  GitHub: https://github.com/Brisoft-ke

  License:
This project is open source and available under the MIT License.
