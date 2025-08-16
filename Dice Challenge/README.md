# 🎲 Dicee – Dice Game

## 📌 Project Overview

This is a simple web-based dice game built with **HTML, CSS, and JavaScript**. Each time the page is refreshed, two dice are rolled randomly for **Player 1** and **Player 2**, and the game automatically declares the winner based on the higher dice value.

The project demonstrates the use of **DOM manipulation, random number generation, and dynamic content updates** with JavaScript.

---

## 🚀 Features

* Two dice roll randomly on every page refresh.
* Player 1 and Player 2 each get one dice.
* The winner is declared automatically:

  * 🚩 *Player 1 Wins!* if Player 1’s dice is greater.
  * *Player 2 Wins! 🚩* if Player 2’s dice is greater.
  * *Draw!* if both dice are equal.
* Clean UI with custom fonts and colors.

---

## 🛠️ Technologies Used

* **HTML5** – For page structure.
* **CSS3** – For styling and layout.
* **JavaScript (Vanilla JS)** – For game logic and interactivity.
* **Google Fonts** – For custom typography.

---

## 📂 Project Structure

```
Dicee/
│
├── index.html       # Main HTML file
├── styles.css       # Styling file
├── index.js         # Game logic (dice roll + winner check)
└── images/          # Dice images (dice1.png to dice6.png)
```

---

## 🎮 How It Works

1. JavaScript generates two random numbers between **1 and 6**.
2. Based on these numbers, the dice images are updated dynamically.
3. The game compares both dice values:

   * If Player 1’s dice > Player 2’s → Player 1 Wins.
   * If Player 2’s dice > Player 1’s → Player 2 Wins.
   * Otherwise → It’s a Draw.

---


## 🌟 Future Improvements

* Add a **"Roll Dice" button** instead of refreshing the page.
* Keep **score tracking** across rounds.
* Add **multiplayer or tournament mode**.
* Improve UI with animations.

---


