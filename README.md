TASK 1.NUMBER GAME 

Enhanced Number Guessing Game
Description

The Enhanced Number Guessing Game is a Java console application where players guess a randomly selected number within a specified range. This version of the game includes features such as setting the maximum number for the range, limiting the number of attempts based on the range, and keeping track of the player's score and high score.

Features

Customizable Range: Players can specify the maximum number for the range within which the target number is selected.
Limited Attempts: The number of attempts allowed for each game is determined based on the maximum number in the range.
Scoring System: Players earn points based on the number of attempts it takes to guess the correct number.
High Score Tracking: The game keeps track of the player's high score across multiple sessions.
Input Validation: Validates user input to ensure it is within acceptable limits and handles invalid inputs gracefully.

Usage

Start the Game: Run the EnhancedNumberGuessingGame class.
Enter the Maximum Number: Specify the maximum number for the range when prompted.
Guess the Number: Enter your guess when prompted and receive feedback on whether your guess is too high, too low, or correct.
Repeat or Exit: After each game, choose whether to play again or exit.

Installation

Clone the repository:
git clone https://github.com/your_username/enhanced-number-guessing-game.git
Navigate to the project directory:
cd enhanced-number-guessing-game
Compile the Java files:
javac EnhancedNumberGuessingGame.java

Run the program:
java EnhancedNumberGuessingGame
Dependencies
Java Development Kit (JDK)


TASK 2.WORD COUNTER

Description

The Word Counter is a Java application that allows users to input text or provide a file to count the number of words. It also provides additional features such as ignoring common words, displaying word frequency, and implementing input validation.

Features

Word Counting: Count the total number of words in the provided text or file.
Ignore Common Words: Exclude common words or stop words from the word count.
Word Frequency: Display the frequency of each word in the input text or file.
Input Validation: Validate user input to handle empty inputs or file errors.
Graphical User Interface (GUI): Provides a user-friendly interface for interacting with the Word Counter.

Usage

Input Text: Enter text directly when prompted.
Provide File: Enter the path of a file to read text from the file.
View Word Count: See the total count of words in the input.
View Word Frequency: See the frequency of each word in the input.

Installation

Clone the repository
git clone https://github.com/your_username/word-counter.git
Navigate to the project directory:

cd word-counter

Compile the Java files:
javac WordCounter.java
Run the program:
java WordCounter
Dependencies
Java Development Kit (JDK)


TASK 3.ATM INTERFACE UNIT

Description

This project implements a simple ATM (Automated Teller Machine) interface in Java. The interface allows users to perform basic banking operations such as checking balance, depositing funds, and withdrawing funds.

Features

Display menu options for checking balance, depositing, withdrawing, and exiting.
Perform actions based on user input, such as displaying balance, depositing funds, and withdrawing funds.
Validate user input to ensure it is within acceptable limits, such as sufficient balance for withdrawals.
Display appropriate messages to the user based on their chosen options and the success or failure of their transactions.

Classes

BankAccount: Represents the user's bank account, storing the account balance and providing methods for depositing and withdrawing funds.
ATM: Represents the ATM machine, providing a user interface for interacting with the bank account.

Usage

Compile the Java files:
javac ATM.java BankAccount.java
Run the ATM interface:

Follow the on-screen prompts to perform banking operations.

Example

Welcome to the ATM
1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Choose an option: 2
Enter deposit amount: 500
Deposit successful. Your new balance is: $1500.0
