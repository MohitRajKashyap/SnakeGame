# Snake Game

A classic Snake game implemented in Java using Swing. Control the snake to eat apples, grow longer, and avoid collisions with walls and itself. The game tracks your current score and highest score during play.

---

## Features

- Classic snake gameplay with arrow key controls
- Growing snake as apples are eaten
- Real-time score and high score tracking
- Simple and clean graphical interface using custom images
- Game over screen with final and highest scores

---

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher installed on your system
- A Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or ability to compile and run Java from the command line

### How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/snake-game.git
   cd snake-game
````

2. Compile the Java files:

   ```bash
   javac -d bin src/SnakeGame/*.java
   ```

3. Run the game:

   ```bash
   java -cp bin SnakeGame.Board
   ```

*Alternatively, open the project in your IDE and run the `Board` class.*

---

## Controls

* Use **Arrow Keys** to change the snake’s direction (Up, Down, Left, Right).
* Avoid hitting the walls or the snake's own body.
* Eat the apples to grow longer and increase your score.

---

## Project Structure

```
snake-game/
│
├── src/
│   └── SnakeGame/
│       ├── Board.java
│       └── resources/
│           ├── apple.png
│           ├── dot.png
│           └── head.png
│
└── README.md

---

## Author

Developed by Mohit Raj Kashyap
Feel free to contribute or report issues!

---

Enjoy the game! 🐍🍎
