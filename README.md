# 🎮 Connect Four AI Game

An intelligent Connect Four game featuring an AI opponent powered by the **Minimax algorithm with Alpha-Beta pruning**. Built with Python and Pygame, this project demonstrates advanced game theory concepts and artificial intelligence techniques.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YIgT4rpfYPA-VdV9nsGeBXQl72D3VbjE)

---

## 📹 Demo

Check out the game in action:

[**Watch Demo Video**](https://drive.google.com/file/d/1jJ_5f-OIHQYCl6uWHzR2UtUvMFfH27Yy/view)

---

## ✨ Features

- **🤖 Intelligent AI Opponent**
  - Minimax algorithm with alpha-beta pruning for optimal decision-making
  - Strategic position evaluation using multiple heuristics
  - Lookahead search to plan moves ahead
  - Three difficulty levels: Easy, Normal, and Hard

- **🎨 Interactive GUI**
  - Built with Pygame for smooth graphics and animations
  - Smooth piece-drop animations
  - Visual feedback for valid/invalid moves
  - Color-coded pieces (Red for Player, Yellow for AI)
  - Classic Connect Four board aesthetic

- **🎯 Game Intelligence**
  - Detects immediate winning moves
  - Blocks opponent's winning opportunities
  - Evaluates board positions strategically
  - Optimized search depth based on difficulty level

- **🔄 User Experience**
  - Win/tie detection with visual indicators
  - Easy restart functionality
  - Responsive controls
  - Natural AI thinking delays for better UX

---

## 🚀 How to Run

### Option 1: Run in Google Colab (Recommended)
Click the "Open in Colab" badge above to run the notebook directly in your browser - no installation needed!

### Option 2: Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/ConnectFour-AI-Game.git
   cd ConnectFour-AI-Game
   ```

2. **Install dependencies:**
   ```bash
   pip install pygame numpy
   ```

3. **Run the game:**
   ```bash
   python connect_four_ai.py
   ```
   *(Or run the Jupyter notebook)*

---

## 🧠 AI Implementation

### Minimax Algorithm with Alpha-Beta Pruning

The AI uses the **Minimax algorithm** to determine optimal moves by:

1. **Evaluating all possible moves** up to a certain depth
2. **Assuming optimal play** from both the AI and opponent
3. **Maximizing** the AI's score while **minimizing** the opponent's score
4. **Alpha-beta pruning** to eliminate unnecessary branch evaluations, significantly improving performance

### Position Evaluation Heuristics

The AI evaluates board positions based on:
- **Four-in-a-row detection** (winning positions)
- **Three-in-a-row with open space** (strong positions)
- **Two-in-a-row with open spaces** (developing positions)
- **Center column control** (strategic advantage)
- **Blocking opponent threats**

### Difficulty Levels

| Difficulty | Search Depth | Description |
|-----------|--------------|-------------|
| **Easy** | 2 | Basic lookahead, good for beginners |
| **Normal** | 4 | Balanced challenge with moderate planning |
| **Hard** | 5+ | Deep search, challenging even for experienced players |

---

## 🛠️ Technologies Used

- **Python 3.x** - Core programming language
- **NumPy** - Efficient board representation and array operations
- **Pygame** - Graphics rendering and user interface
- **Jupyter Notebook** - Interactive development and documentation

---

## 📊 Game Architecture

```
Connect Four AI Game
│
├── Board Representation (NumPy arrays)
├── Game Logic
│   ├── Move validation
│   ├── Win detection
│   └── Board state management
│
├── AI Engine
│   ├── Minimax algorithm
│   ├── Alpha-beta pruning
│   ├── Position evaluation
│   └── Move selection
│
└── User Interface (Pygame)
    ├── Board rendering
    ├── Animation handling
    ├── Event management
    └── Visual feedback
```

---

## 🎯 Key Concepts Demonstrated

- **Game Theory** - Minimax algorithm for adversarial search
- **Algorithm Optimization** - Alpha-beta pruning to reduce computational complexity
- **Heuristic Evaluation** - Strategic position scoring
- **Object-Oriented Design** - Clean, modular code structure
- **GUI Development** - Interactive game interface with Pygame

---

## 📝 Project Structure

```
ConnectFour-AI-Game/
│
├── Connect_Four_AI_Game.ipynb    # Main Jupyter notebook with full implementation
├── README.md                      # This file
└── requirements.txt               # Python dependencies
```

---

## 🎮 How to Play

1. **Launch the game** using one of the methods above
2. **Click on a column** to drop your piece (Red)
3. **The AI responds** with its move (Yellow)
4. **First to connect four** pieces horizontally, vertically, or diagonally wins!
5. **Press 'R'** to restart the game at any time

---

## 🔮 Future Enhancements

- [ ] Machine learning-based AI using reinforcement learning
- [ ] Multiplayer mode (Player vs Player)
- [ ] Online multiplayer support
- [ ] Move history and undo functionality
- [ ] Save/load game states
- [ ] Tournament mode with statistics tracking
- [ ] Mobile version

---

## 👨‍💻 Author

**Rayyan Afzal**

---

## 📄 License

This project is open source and available for educational purposes.

---

## 🙏 Acknowledgments

- Classic Connect Four game mechanics
- Minimax algorithm implementation inspired by game theory literature
- Pygame community for excellent documentation and resources

---

**Enjoy the game! 🎉**
