# 🥁 Drum Kit

An interactive **drum kit web app** built using **HTML, CSS, and JavaScript**.
Click the buttons or press the corresponding keys on your keyboard to play different drum sounds!

---

## 🚀 Features

* 🎹 **Play with Mouse & Keyboard**

  * Click on drum buttons, or press keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`).
* 🎶 **Real Drum Sounds**

  * Each button plays a different drum sound (tom, snare, crash, kick).
* 💡 **Visual Feedback**

  * Buttons highlight with an animation (`pressed` effect) when played.
* 🎨 **Custom Styling**

  * Attractive design with background images for each drum.

---

## 🛠️ Technologies Used

* **HTML5** – for structure
* **CSS3** – for styling & animations
* **JavaScript (ES6)** – for event handling and audio playback

---

## 🎯 How It Works

1. **Event Listeners**

   * Each button listens for a click event.
   * The entire document listens for `keypress` events.

2. **Sound Playback**

   * Depending on the key pressed (e.g., `w`, `a`, `s`), the corresponding `.mp3` file is played using the `Audio()` constructor.

3. **Button Animation**

   * The `buttonEffect()` function temporarily applies the `pressed` CSS class, creating a visual effect.

---

## 🎹 Controls

| Key | Drum Sound |
| --- | ---------- |
| w   | Tom 1      |
| a   | Tom 2      |
| s   | Tom 3      |
| d   | Tom 4      |
| j   | Crash      |
| k   | Kick Bass  |
| l   | Snare      |

---

## 📸 Preview

(Add a screenshot or GIF of your project here for better visuals)

---

## 📂 Project Structure

```
drum-kit/
│
├── index.html      # Main HTML file
├── styles.css      # Styling
├── index.js        # JavaScript logic
├── sounds/         # Drum sound files
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   ├── tom-3.mp3
│   ├── tom-4.mp3
│   ├── crash.mp3
│   ├── kick-bass.mp3
│   └── snare.mp3
├── images/         # Drum images
└── README.md       # Documentation
```

---

## 💻 Setup

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/drum-kit.git
   ```
2. Open `index.html` in your browser.
3. Start playing drums 🥁

---
