# Knights Travails

This is an assignment from The Odin Project regarding finding the **shortest path** for a knight on a chessboard using **Breadth-First Search (BFS)**. The knight moves in "L" shapes, and the program outputs the shortest sequence of moves from a starting position to a target.

---

## How It Works

- The chessboard is an 8x8 grid.
- Each square is represented by coordinates `[x, y]`, where `0 <= x, y <= 7`.
- The program uses BFS to explore all possible knight moves, ensuring the shortest path is found.

---

## Example Input and Output

1. **Input**: `knightMoves([0, 0], [1, 2])`

   - **Output**:
     ```
     You made it in 1 moves! Here's your path:
     [0, 0]
     [1, 2]
     ```
2. **Input**: `knightMoves([0, 0], [3, 3])`

   - **Output**:
     ```
     You made it in 2 moves! Here's your path:
     [0, 0]
     [2, 1]
     [3, 3]
     ```

---

## Code Overview

- **Function**: `knightMoves(start, end)`
- **Parameters**:
  - `start`: Knight's starting position `[x, y]`.
  - `end`: Target position `[x, y]`.
- **Logic**:
  - Validates positions.
  - Uses BFS to explore paths.
  - Stops when the shortest path to the target is found.

---

**@Mainul Islam**
