# Tic-Tac-Toe 

A simple 2-player Tic-Tac-Toe (Noughts and Crosses) game played in the terminal. Built using Java.

---

## 🎮 Gameplay

- The game is played on a 3x3 grid.
- Two players take turns: Player `X` and Player `O`.
- A player wins by placing 3 of their marks in a row, column, or diagonal.
- If the grid is filled and no player has won, the game ends in a tie.

---

## 💡 Example Input & Output

```
-----------
|   |   |   | 
-----------
|   |   |   | 
-----------
|   |   |   | 
-----------
Player X, it's your turn.
Enter row (1-3): 1
Enter column (1-3): 1
-----------
| X |   |   | 
-----------
|   |   |   | 
-----------
|   |   |   | 
-----------
Player O, it's your turn.
Enter row (1-3): 2
Enter column (1-3): 2
-----------
| X |   |   | 
-----------
|   | O |   | 
-----------
|   |   |   | 
-----------
...
```

---

## 🚀 How to Run

1. Make sure you have Java installed. You can check with:
   ```bash
   java -version
   ```

2. Compile the Java file:
   ```bash
   javac Main.java
   ```

3. Run the compiled program:
   ```bash
   java Main
   ```

---

## 🛠️ Requirements

- Java 8 or higher
- Terminal or command prompt

---

## 🗃️ Project Structure

```
.
├── Main.java         # Main game logic
├── .gitignore        # Git ignore rules
└── README.md         # Project documentation
```

---

## 📝 License

This project is open-source and free to use for educational purposes.
