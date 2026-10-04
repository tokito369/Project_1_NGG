# 🎯 Number Guessing Game

A simple command-line game written in C where you try to guess a secret number chosen by the computer.

## ✨ Technologies

* C
* Standard libraries: `stdio.h`, `stdlib.h`, `time.h`

## 🚀 Features

* **Random Secret Number:** The computer picks a new number every game using `rand()` seeded with the current time.
* **Hints After Every Guess:** Tells you whether your guess is too high or too low.
* **Attempt Counter:** Tracks how many tries it took you to find the number.
* **Replay Option:** Play again without restarting the program.
* **Runs in the Terminal:** No dependencies and no setup beyond a C compiler.

## 📍 The Process

I built this project to practice the fundamentals of C programming: loops, conditionals, user input/output, and random number generation. A guessing game is small enough to finish quickly but still covers the core concepts, like `while` loops, `if-else` logic, and `scanf` for input. The focus was keeping the code clean and the gameplay simple so the logic is easy to follow.

## 🚦 Running the Project

1. Clone this repository to your local machine.
2. Make sure you have a C compiler installed (such as GCC).
3. Compile the program:
```bash
   gcc guessing_game.c -o guessing_game
```
4. Run it:
```bash
   ./guessing_game
```
   On Windows, use `guessing_game.exe` instead.
5. Start guessing!

## 🎮 How to Play

1. The computer picks a number between 1 and 100.
2. Enter your guess.
3. Follow the hints (too high or too low) until you find the number.
4. Your total attempts are shown when you win.

## 🎞️ Preview

*(coming soon...)*
