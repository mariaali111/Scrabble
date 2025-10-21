# 🧩 Scrabble (C)

A simple **two-player Scrabble-style game** written in C.  
Each player enters a word, and the program computes a score based on Scrabble letter values to determine the winner.

---

## 🕹️ How It Works
- Each letter has a score (A = 1, B = 3, C = 3, ..., Z = 10).  
- Both players enter a word.  
- The program calculates each word’s total score.  
- The player with the higher score wins — or it’s a tie!

---

## 💻 Example Run
Player 1: HELLO
<br>
Player 2: WORLD
<br>
Player 2 wins!

---

## 🎯 Concepts Used
- Character arrays (strings)
- ASCII arithmetic
- Conditionals (if, else)
- Functions and arrays

---

## 📁 File Structure
📂 scrabble
<br>
 ├── scrabble.c      # Main program
<br>
 └── README.md       # Project description

 ---
 
## ⚙️ How to Compile and Run
Make sure you have GCC or any C compiler installed.

```bash
# Compile
gcc scrabble.c -o scrabble

# Run
./scrabble
```


