# java-projects
Here’s a `README.md` for your Java-based *Dino Game* project:

---

# 🦖 Dino Game in Java

A simple 2D side-scroller game built in Java, inspired by the classic offline Chrome Dino Game. The dinosaur jumps over cacti and tries to survive as long as possible. This project demonstrates basic game loop mechanics, keyboard controls, object drawing, and collision detection using Java AWT and Swing libraries.

---

## 🎮 Features

- Jumping dinosaur controlled by the `Enter` key
- Randomly generated cacti as obstacles
- Simple collision detection
- Game Over screen with restart functionality (`Space` key)
- Hand-drawn game elements using basic graphics

---

## 🛠️ Technologies Used

- **Java AWT** and **Swing** for GUI and rendering
- `Timer` for game loops and animations
- Basic OOP concepts (encapsulation, inheritance, event handling)

---

## 🚀 How to Run

1. **Clone or Download the Project**
   ```
   git clone https://github.com/your-username/dino-game-java.git
   cd dino-game-java
   ```

2. **Compile the Code**
   ```
   javac dino.java
   ```

3. **Run the Game**
   ```
   java Game
   ```

> Make sure you have JDK installed and properly configured in your system's PATH.

---

## 🎮 Controls

| Key      | Action                |
|----------|------------------------|
| `Enter`  | Make the dinosaur jump |
| `Space`  | Restart after game over |

---

## 🧠 How It Works

- The game window is set to `1200x550` pixels.
- The dinosaur is drawn pixel-by-pixel using rectangles.
- Obstacles (cacti) are randomly generated and move from right to left.
- Collision is detected using X and Y coordinate checks.
- Two separate `Timer`s are used: one for obstacle movement and one for jump motion.

---

## 📸 Preview

*(Add screenshots or GIF here if you want to show gameplay)*

---

## 📂 Folder Structure

```
.
├── dino.java         # Main game source code
└── README.md         # Project documentation
```

---

## 📌 Future Enhancements

- Add score tracking
- Add sound effects
- Introduce multiple difficulty levels
- Implement a pause/resume feature


