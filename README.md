# ♛ N-Queen Problem Solver (C++)

A collection of C++ implementations to solve the classic N-Queen puzzle. This project explores backtracking, recursion, and optimization techniques.

> **Note:** The core logic was developed independently to strengthen understanding of recursive state-space trees.

## 📌 About the N-Queen Problem

The N-Queen problem is a classic algorithmic challenge where:

- You must place **N queens** on an **N × N chessboard**
- No two queens should attack each other
- Queens must not share the same:
  - Row
  - Column
  - Diagonal

This program finds and prints all valid solutions.

## ⚙️ Features

- Uses recursion and backtracking
- Prints all valid solutions
- Displays each solution as a sequence of column positions
- Counts total valid arrangements

## 🧠 How the Program Works

- Each row represents a queen
- `a[row]` stores the column position of that queen
- The program:
  1. Places queens row by row
  2. Checks for attacks
  3. Backtracks if a position is unsafe
  4. Prints solutions when found

## ▶️ Input (Example for N = 4)

When you run the program, enter the size of the board (N):

```txt
Enter the size of queens:
4
Goal-1: 2 4 1 3
Goal-2: 3 1 4 2
```

## 🚀 Learning Outcome

Through this project, I learned:

- Recursive function design
- Backtracking techniques
- Logical problem-solving
- Handling arrays and conditions in C++

"This project significantly increased my confidence in solving algorithmic problems independently."

## 👨‍💻 Author

**Sameer Dangaura**

- Beginner C++ Programmer
- Focus: Data Structures & Algorithms
