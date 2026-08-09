# 🎮 Flappy Bird 2.0

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com/)
[![Swing](https://img.shields.io/badge/Swing-GUI-6DB33F?style=for-the-badge&logo=java)](https://docs.oracle.com/javase/8/docs/technotes/guides/swing/)
[![AWT](https://img.shields.io/badge/AWT-Graphics-007396?style=for-the-badge&logo=java)](https://docs.oracle.com/javase/8/docs/technotes/guides/awt/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/GitHub-View-181717?style=for-the-badge&logo=github)](https://github.com/mastersflash19/flappy-bird-2.0)

---

## 📖 Description

**Flappy Bird 2.0** is a recreation of the classic Flappy Bird game built with **Java Swing** and **AWT**. This project was developed as a collaborative effort by **Team Apollo** to demonstrate proficiency in GUI development, event-driven programming, and game development fundamentals.

---

## 👥 Team Apollo

| Role | Name |
|------|------|
| **Team Member** | Lutho Sigodi |
| **Team Member** | Abona Ntsaluba |
| **Team Member** | **Tshephang Makgaloa** |
| **Team Member** | Okoyama Nomafaku Tantsi |
| **Mentor** | Sinenjabulo Gogwana |

---

## 🎯 Features

- 🐦 **Classic Gameplay** - Tap/space to make the bird fly
- 🎨 **Colorful Graphics** - Built with Java AWT
- 🏗️ **Random Pipe Generation** - Infinite obstacle course
- 📊 **Score Tracking** - Keep track of your score
- 🏆 **Medal System** - Earn Bronze, Silver, Gold, and Platinum medals
  - 🥉 **Bronze** - Score ≥ 10
  - 🥈 **Silver** - Score ≥ 50
  - 🥇 **Gold** - Score ≥ 100
  - 💎 **Platinum** - Score ≥ 200
- 🎵 **Sound Effects** - Background music
- ⌨️ **Keyboard Controls**
  - **SPACEBAR** - Flap wings
  - **P** - Pause game
  - **R** - Resume game
  - **S** - Restart game
- 📱 **Mouse Support** - Click to restart after game over

---

## 📸 Screenshots

### Start Screen
The main menu with the game title and PLAY button.

![Start Screen](assets/screenshots/start-screen.png)

### Gameplay
In-game view showing the bird navigating through pipes with score display and controls.

![Gameplay](assets/screenshots/gameplay.png)

### Gameplay with Score
Active gameplay showing the score counter and keyboard controls.

![Gameplay with Score](assets/screenshots/gameplay-score.png)

### Game Over Screen
Game over screen displaying your final score with option to restart.

![Game Over](assets/screenshots/game-over.png)

### Additional Screenshots

| Start Screen | Gameplay |
|--------------|----------|
| ![Start Screen 2](assets/screenshots/start-screen2.png) | ![Gameplay 2](assets/screenshots/gameplay2.png) |

---

## 🎮 How to Play

### Controls

| Key | Action |
|-----|--------|
| **SPACEBAR** | Make the bird flap and fly upward |
| **P** | Pause the game |
| **R** | Resume the game |
| **S** | Restart the game |
| **Click** | Restart after game over |

### Game Rules
1. Press **SPACEBAR** to make the bird flap and gain altitude
2. Navigate through the gaps between pipes
3. Each gap passed = **0.5 points** (displayed as whole numbers)
4. Game ends if you hit a pipe or the ground
5. Try to beat your high score and earn medals!

### Medal System
- 🥉 **Bronze Medal** - Reach score 10
- 🥈 **Silver Medal** - Reach score 50
- 🥇 **Gold Medal** - Reach score 100
- 💎 **Platinum Medal** - Reach score 200

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Java** | Core programming language |
| **Swing** | GUI framework (JFrame, JPanel, JButton) |
| **AWT** | Graphics rendering and event handling |
| **javax.sound** | Audio playback for background music |
| **ArrayList** | Storing pipe objects |
| **Random** | Random pipe generation |
| **Timer** | Game loop and pipe spawning |

### Key Java Concepts Applied
- ✅ Variables and Data Types
- ✅ Classes and Objects
- ✅ Inheritance
- ✅ Inner Classes
- ✅ Exception Handling
- ✅ Event-Driven Programming (ActionListener, KeyListener)
- ✅ Collections (ArrayList)
- ✅ Graphics (paintComponent)
- ✅ Timer for game loop
- ✅ Random number generation

---

## 🚀 Installation

### Prerequisites
- **Java JDK 8** or higher
- **Git** (for cloning)

### Steps

```bash
# Clone the repository
git clone https://github.com/mastersflash19/flappy-bird-2.0.git

# Navigate to project directory
cd flappy-bird-2.0

# Compile the code
javac -d out src/*.java

# Run the game
java -cp out App
