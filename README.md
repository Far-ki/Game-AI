#  Path Tracing Game

A simple browser-based game built with HTML, CSS, and JavaScript where the player selects a path from a randomly chosen start point to a goal point, aiming to minimize the total cost of the path.

---

##  Game Rules

- The board is a 5x5 grid with randomly generated values ranging from **-5 to 9**.
- The **start point** is randomly placed on the edge (highlighted in **blue**).
- The **end point** is also randomly placed on an edge (highlighted in **red**) and is at least 5 tiles away.
- The player can move **only to adjacent tiles** (up, down, left, right).
- Each clicked tile is added to the player's path (**green**).
- When the player reaches the goal, the game displays:
  - The **total cost** of the player's path
  - The **best possible path** (**gold**) calculated using DFS

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Far-ki/Game-AI.git
   ```
