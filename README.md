#TASK 1
# Number Guessing Game

## Overview
This project is a simple number-guessing game where the user attempts to guess a randomly generated number within a specified range. The game provides feedback on whether the guess is too high, too low, or correct. Players are limited by a set number of attempts and can play multiple rounds, with their score being tracked based on the number of attempts or rounds won.

## Features
- **Random Number Generation**: The game generates a random number within a specified range (e.g., 1 to 100).
- **User Input**: The user is prompted to guess the generated number.
- **Feedback**: After each guess, the game provides feedback to let the user know whether their guess was too high, too low, or correct.
- **Limited Attempts**: Users are allowed a limited number of attempts to guess the correct number.
- **Multiple Rounds**: Players can play multiple rounds, with a new random number generated for each round.
- **Score Tracking**: The game tracks and displays the user's score, which can be based on the number of attempts used or rounds won.

## How to Play
1. The game will generate a random number between 1 and 100.
2. You will be prompted to guess the number.
3. After each guess, the game will tell you if your guess was too high, too low, or correct.
4. If you guess the number correctly, the game will display your score and give you the option to play again.
5. The game ends when you either guess the number correctly or run out of attempts.

#TASK2
# **Student Grade Calculation**

## **Overview**
This project calculates a student's grade based on their performance in various subjects. The user will input the marks obtained in each subject, and the system will compute the total marks, average percentage, and assign a grade based on the percentage. The system then displays the results for the user.

## **Features**
- **Input Marks**: The user is prompted to enter the marks they received in each subject (out of 100).
- **Total Marks Calculation**: The system adds up all the marks across the subjects to get the total marks.
- **Average Percentage Calculation**: The system calculates the average percentage by dividing the total marks by the total number of subjects and scaling it based on the maximum possible marks.
- **Grade Calculation**: Based on the average percentage, the system assigns a grade using a predefined grading scale.
- **Result Display**: After the calculations, the system displays the total marks, average percentage, and the grade.

## **Grading Scale Example**
The grading scale used to determine the grade based on the average percentage is as follows:

- **Grade O**: 90% above
- **Grade A+**: 81% to 90%
- **Grade A**: 71% to 80%
- **Grade B+**: 61% to 70%
- **Grade B**: 51% to 60%
- **Grade C**: 41% to 50%
- **Grade D**: 35% to 40%
- **Grade Fail**: below 35%

## **How to Use**
1. **Input the Marks**: The user will input their marks for each subject (out of 100).
2. **Total Marks**: The system will calculate the total of all the marks entered.
3. **Average Percentage**: The system will compute the average percentage by dividing the total marks by the total possible marks and multiplying by 100.
4. **Grade Assignment**: Based on the average percentage, the system will assign a grade (O, A+ ,A, B+, B, C, D or Fail).
5. **Display Results**: Finally, the system will display:
   - **Total Marks**
   - **Average Percentage**
   - **Assigned Grade**

## **Example Walkthrough**

### **Input**:
Let’s assume the student has marks in the following subjects:
- **Marks in Subject 1**: 85
- **Marks in Subject 2**: 90
- **Marks in Subject 3**: 75
- **Marks in Subject 4**: 88

### **Process**:
1. **Total Marks**: The system sums up the marks for all subjects:  
   85 + 90 + 75 + 88 = **338** total marks.
   
2. **Average Percentage**: The system calculates the average percentage:
   \[
   \text{Average Percentage} = \left(\frac{338}{400}\right) \times 100 = 84.5\%
   \]
   
3. **Grade Calculation**: Based on the average percentage of **84.5%**, the student falls under **Grade B** according to the grading scale.

### **Output**:
- **Total Marks**: 338
- **Average Percentage**: 84.5%
- **Grade**: B




#TASK 3

### **ATM Machine Simulation**
A Java-based program simulating an ATM machine with essential banking operations such as withdrawing, depositing, and checking balance. The program includes input validation, a simple user interface, and meaningful error messages.

### **Features**
**Check Balance**: 
Allows the user to view their current account balance.
**Deposit Money**:
Enables the user to add money to their account.
**Withdraw Money**:
Allows the user to withdraw money if sufficient balance is available.
**Exit**:
Ends the ATM session.

### **How It Works**

### **The BankAccount class:**

Stores the user's account balance.
Provides methods for depositing, withdrawing, and checking the balance.
Validates inputs to ensure proper operation (e.g., no negative deposits or withdrawals exceeding the balance).
The ATM class:

Provides a user-friendly menu-driven interface.
Integrates with the BankAccount class to perform operations based on user choices.
Handles invalid inputs and displays appropriate messages.

### **The Main class:**

Creates a bank account with an initial balance.
Instantiates the ATM and connects it to the bank account.
Displays the menu and processes user inputs in a loop.

### **Output**:
**ATM Menu:**
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
Enter your choice: 1
Your current balance is: 1000.0

**ATM Menu:**
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
Enter your choice: 2
Enter amount to deposit: 500
Successfully deposited: 500.0

**ATM Menu:**
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
Enter your choice: 3
Enter amount to withdraw: 300
Successfully withdrawn: 300.0

**ATM Menu:**
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
Enter your choice: 4
Thank you for using the ATM. Goodbye!
