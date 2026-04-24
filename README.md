# Rock Paper Scissors Web Game 🪨 📄 ✂️

A clean, interactive Rock Paper Scissors game built with vanilla JavaScript, HTML, and CSS. This project features a persistent scoring system and a modern dark-themed interface.

## ✨ Features
* **Persistent Scoring:** Keeps track of your Wins, Losses, and Ties even after refreshing the page using `localStorage`.
* **Dynamic UI:** Real-time updates for game results and move selections using DOM manipulation.
* **Visual Feedback:** Displays custom emoji icons for both the player and the computer's moves.
* **Score Reset:** Option to clear all stored data and start a new session.

## 🚀 How to Play
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AyeshaShiham/Rock-Paper-Scissors.git](https://github.com/AyeshaShiham/Rock-Paper-Scissors.git)
    ```
2.  **Run the game:** Open `index.html` in any web browser.
3.  **Make your move:** Click on the Rock, Paper, or Scissors icons to play against the computer.
4.  **Reset:** Click the "Reset Score" button to wipe the record.

## 🛠️ Built With
* **HTML5** - Page structure and layout.
* **CSS3** - Custom styling, flexbox, and circular button designs.
* **JavaScript (ES6)** - Game logic, random move generation, and local storage management.

## 📂 Project Structure
* `index.html`: The main structure of the game.
* `rps.css`: The styling rules for the dark theme and UI elements.
* `rps.js`: The logic handling computer moves, score tracking, and UI updates.

## 📝 Game Logic
The computer move is determined by a random number generator:
* $0 \le x < \frac{1}{3} \rightarrow$ **Rock**
* $\frac{1}{3} \le x < \frac{2}{3} \rightarrow$ **Paper**
* $\frac{2}{3} \le x < 1 \rightarrow$ **Scissors**

---
Developed by [Ayesha Shiham](https://github.com/AyeshaShiham)
