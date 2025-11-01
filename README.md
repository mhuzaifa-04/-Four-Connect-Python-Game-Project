# Connect Four Game in Python

This is a classic "Connect Four" (or "Four Connect") game built from scratch using Python. It features a complete graphical user interface (GUI) and supports two-player gameplay.

### Demo

![A demo of the Connect Four game in action. Player 2 (Yellow) wins with a vertical line.]([https://i.imgur.com/8N4JpZt.png](https://www.askpython.com/wp-content/uploads/2021/04/c4.jpg.webp))

*(**Note:** You can create a GIF from your video and replace the image link above to show the game in action! A tool like [Ezgif](https://ezgif.com/video-to-gif) is great for this.)*

---

## 📜 Description

This project is a Python implementation of the two-player connection game, Connect Four. The game was built to practice game logic, algorithm design (specifically for win-checking), and GUI development with Pygame.

The game board is managed by a **NumPy** array, which allows for efficient updates and checking. All graphics, user input (mouse clicks), and event handling are managed by the **Pygame** library.

---

## ✨ Features

* **Full Two-Player Game:** Play against a friend, alternating turns as Red (Player 1) and Yellow (Player 2).
* **Graphical Interface:** A clean and responsive game board rendered with Pygame.
* **Mouse-Based Input:** Simply click the column where you want to drop your piece.
* **Real-time Visuals:** Pieces fall into place and the board updates instantly.
* **Comprehensive Win Detection:** The game automatically checks for and detects wins in all four directions:
    * Horizontal
    * Vertical
    * Positively-sloped Diagonal
    * Negatively-sloped Diagonal
* **Game Over Message:** A "Player X Wins!" message is displayed on-screen when a player wins.

---

## 🛠️ Tech Stack

* **Python 3**
* **Pygame:** The core library for graphics, event handling, and rendering the game window.
* **NumPy:** Used to create and efficiently manage the 2D array that represents the game board's state.

---

## 🚀 Getting Started

### Prerequisites

You must have **Python 3** installed on your system.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd YOUR_REPOSITORY_NAME
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    # On Windows
    python -m venv venv
    venv\Scripts\activate

    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
    *(**Note:** If you don't have a `requirements.txt` file, you can just install the packages manually)*
    ```bash
    pip install pygame numpy
    ```

### How to Run

Execute the main Python script to start the game:

```bash
python four_connect.py
```
*(Replace `four_connect.py` with the name of your main Python file if it's different.)*

---

## 🎮 How to Play

1.  Run the script to launch the game window.
2.  The board will appear. Player 1 is **Red** and Player 2 is **Yellow**.
3.  Player 1 starts. Click on any column to drop your piece.
4.  The piece will fall to the lowest available spot in that column.
5.  Players alternate turns.
6.  The first player to get **four of their pieces in a row** (horizontally, vertically, or diagonally) wins the game!
