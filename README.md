# Descending Numbers Game

**Objective:**
Fill all five slots with numbers in strictly descending order (from highest at the top to lowest at the bottom).

**How to Play:**

1. Press **Generate** to produce a random number between 1 and 100.
2. The number appears in a draggable box.
3. Drag the box and drop it into one of the empty slots.

   * You must place it so that all numbers above it are larger and all numbers below it are smaller.
4. Once placed, the number is locked in and cannot be moved.
5. Continue generating numbers and filling slots until all five are filled.

**Rules:**

* You cannot generate a new number until you place the current one.
* Each number must maintain descending order across the list.
* If no valid slot exists for a newly generated number, the game ends in a **loss**.
* If you fill all slots successfully in descending order, you **win**.

**Modes:**

* **Normal Mode:** A single round — win or lose ends the game.
* **Endless Mode:** Play multiple rounds in a row. Each win increases your win counter. Losing resets the counter. Resetting after a win keeps your streak alive.

**Controls:**

* **Generate:** Creates a new random number.
* **Drag & Drop:** Place the number in an empty slot.
* **Reset Game:** Clears the board. In Endless mode, resets counter only if you lose or reset mid-game.
