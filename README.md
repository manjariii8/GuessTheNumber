# 🎮 Number Guessing Game

A simple Java console-based **Number Guessing Game** developed as **Task 1** for the **CodSoft Java Programming Internship**.

## 📌 Project Description

In this game, the computer randomly generates a number between **0 and 99**, and the player tries to guess it. After each guess, the program provides feedback indicating whether the guessed number is **too high**, **too low**, or **correct**. It also keeps track of the total number of attempts taken to guess the number.

## ✨ Features

* Random number generation using Java's `Random` class.
* User-friendly console interaction.
* Provides hints after every incorrect guess.
* Counts the number of attempts.
* Displays the player's score after each round.
* Option to play multiple rounds.

## 🛠️ Technologies Used

* Java
* Scanner Class
* Random Class
* Console-Based Application

## 📂 Project Structure

```
NumberGuessingGame/
│
├── CodsoftTask_1.java
└── README.md
```

## ▶️ How to Run

1. Clone the repository or download the source code.

```bash
git clone < https://github.com/manjariii8/GuessTheNumber.git>
```

2. Navigate to the project directory.

```bash
cd GuessTheNumber
```

3. Compile the Java program.

```bash
javac CodsoftTask_1.java
```

4. Run the program.

```bash
java CodsoftTask_1
```

## 🎯 How to Play

1. The computer randomly selects a number between **0 and 99**.
2. Enter your guess.
3. The program will display:

   * **Too High** if your guess is greater than the generated number.
   * **Too Low** if your guess is less than the generated number.
   * **Guess number is correct** when you guess the correct number.
4. Your total number of attempts is displayed at the end of the round.
5. Choose whether to play another round.

## 📷 Sample Output

```
Enter your number less than 100:
45
Too low.

Enter your number less than 100:
72
Too high.

Enter your number less than 100:
61
Guess number is correct.

*********************Displaying Scorecard of Player**************************

Number of attempts to guess the number in 1 round is: 3

Do you want to play again? (yes/no):
```

## 📚 Concepts Used

* Java Basics
* Loops (`do-while`, `while`)
* Conditional Statements (`if-else`)
* Random Number Generation
* User Input using `Scanner`
* Variables and Counters

## 🚀 Future Improvements

* Limit the maximum number of attempts.
* Add multiple difficulty levels (Easy, Medium, Hard).
* Generate a new random number for every new round.
* Maintain a high-score leaderboard.
* Validate invalid user input.
* Improve score calculation based on the number of attempts.

## 👩‍💻 Author

**Manjari Tripathi**

B.Tech Computer Science & Engineering Student

Java | Backend Development | DSA | Spring Boot | Software Engineering

---

**CodSoft Java Programming Internship – Task 1**
