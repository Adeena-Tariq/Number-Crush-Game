# Number Crush Game 🎮

A console-based **Match-3 Puzzle Game** developed in **x86 Assembly Language** using the **Irvine32 Library**.  
The project is inspired by games like Candy Crush and demonstrates how interactive game mechanics can be implemented using low-level programming concepts.

---

## 📌 Project Overview

Number Crush Game is an academic project created for the **Computer Organization & Assembly Language (COAL)** course.  
The game focuses on array manipulation, logical operations, memory handling, file processing, and gameplay implementation completely in Assembly Language.

The player swaps adjacent numbers to create combinations of 3 or more matching elements.  
The game includes bombs, score tracking, multiple levels, and permanent player record storage.

---

## ✨ Features

-  Three different gameplay levels
-  Colored console game board
-  Bomb explosion mechanics
-  Match-3 combo detection
-  Invalid move detection
-  Automatic reverse swap if no combo occurs
-  Score calculation system
-  Randomized board generation
-  Block cells in advanced level
-  File handling using `PlayersRecord.txt`
-  Player name input and score saving

---

## 🕹️ Game Levels

### Level 1
- Board Size: 10 × 10
- Elements: Numbers (1–5) + Bombs
- Focus: Basic gameplay and combo logic

### Level 2
- Board Size: 9 × 9
- Elements: Numbers, Bombs, Empty Spaces
- Focus: Restricted movement and obstacles

### Level 3
- Board Size: 10 × 10
- Elements: Numbers, Bombs, Block Cells (X)
- Focus: Advanced gameplay difficulty

---

## 📜 Game Rules

- Only adjacent swaps are allowed
- Diagonal swaps are not allowed
- Bomb-to-bomb swaps are restricted
- Block cells cannot be swapped
- A move must create at least one valid combo
- Invalid moves are automatically reversed
- Bomb explosions remove matching elements
- Each crushed element increases the score
- Each level allows only 2 valid moves

---

## 🛠️ Technologies Used

- x86 Assembly Language
- Irvine32 Library
- Visual Studio / MASM
- Console-based Interface

---

## 📂 Data Structures Used

- 2D Arrays (10×10 and 9×9)
- Variables for:
  - Score
  - Moves
  - Levels
  - Player Name
- Text File Handling (`PlayersRecord.txt`)

---

## ⚙️ Functional Workflow

1. Game starts with a welcome screen
2. Player enters name
3. Random board is generated
4. Player performs valid swaps
5. Combos and bombs are processed
6. Score is updated
7. Results are stored in a file
8. Highest score is displayed at the end

---

## 📥 Input

- Player name
- Array indexes for swapping positions

---

## 📤 Output

- Colored game board
- Player information panel
- Combo and bomb messages
- Final score records

---

## 📁 File Handling

The project stores player records inside:

```txt
PlayersRecord.txt
