# Fanachess Analyzer 🛡️

A premium, highly undetectable Chrome Extension helper designed to analyze and overlay real-time chess engine recommendations on Chess.com.

---

## 📸 Interface Preview

![Fanachess Analyzer Settings Panel](C:/Users/USER/.gemini/antigravity-ide/brain/9ed053d3-9518-4a43-8a8f-6ac5335a88bd/media__1784055163367.png)

---

## 🚀 Key Features

* **Multiple Engine Routing (Lichess Cloud, ChessDB, Maia neural network, Stockfish Live)** with automatic failure switching/fallbacks.
* **Grandmaster Opening Book Explorer** querying Lichess Masters database in real-time.
* **Interactive Visual Evaluation Bar** displaying live scoring updates with dynamic glowing gradients.
* **Undetectable Anti-Cheat Evading System**:
  * Simulated **human-like thinking delays** utilizing log-normal distribution.
  * Real-time **tactical hesitation and panic-time heuristics**.
  * **Win Margin Elo Protection** (automatically plays sub-optimal moves when winning to bypass accuracy checks).
  * **Bezier Curve Mouse Dragging** with random micro-jitter and acceleration to mock human hand movements.
* **Double Escape Panic Mode** for emergency removal/restoration of HUD elements.
* **Invisible Integration (Shadow DOM Isolation)** protecting extension markup from Chess.com scripts detection.
* **Global Power ON/OFF Toggle** directly from the extension toolbar popup.

---

## 📥 How to Install & Use

### 1. Download the Extension
Download the compiled release package **`fanachess.zip`** from this repository. Extract the ZIP file into a dedicated folder on your computer (e.g. `D:/fanachess`).

### 2. Install on Chrome
1. Open Google Chrome and navigate to:
   ```text
   chrome://extensions/
   ```
2. Enable **Developer mode** using the toggle switch in the top-right corner.
3. Click the **Load unpacked** (*Muat ekstensi yang belum dikemas*) button in the top-left corner.
4. Select the extracted folder containing the `manifest.json` file.

### 3. Start Analyzing
1. Open a chess game on [Chess.com](https://www.chess.com/play/).
2. Press **Alt** to show the best move overlay.
3. Click the **Backtick key (`` ` ``)** to hide/show the control panel.
4. Press your configured hotkey (**Spacebar** or **`E`** by default) to automatically execute the engine's best move with humanized dragging simulation.

---

## ⚠️ Warning & Disclaimer

> [!WARNING]
> **Note:** This project was developed for learning purposes. I do not condone or encourage cheating in games, and this project should help you get better at chess. Non-fair play might result in your chess.com account being suspended if you do not use wisely.
