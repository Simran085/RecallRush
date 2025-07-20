# 🧠 Simon’s Game – Memory Challenge with JavaScript

> A fun and interactive browser-based memory game inspired by the classic Simon electronic toy. Built with pure HTML, CSS, and JavaScript.

---

## 🎯 Objective

**Simon’s Game** tests your memory by challenging you to recall and repeat an ever-growing sequence of colors and sounds. With each successful round, a new color is added, increasing the difficulty and pushing your cognitive limits.

---

## 🚀 Key Features

### 🔁 Random Sequence Generation  
- Every round, the game adds a **random color** to the sequence.  
- Sequences grow progressively harder to test player memory.

### 🖱️ Intuitive User Interaction  
- Clickable color buttons with **instant visual and audio feedback**.  
- Smooth and responsive gameplay that feels natural across devices.

### ❌ Error Feedback & Reset  
- If you click the wrong button, an **error sound** plays and the game resets.  
- Players can restart immediately and try again to beat their high score.

### 🧮 Score Tracking  
- Score increases with each correctly replicated sequence.  
- Motivates players to challenge themselves and improve.

### 📱 Responsive Design  
- Works seamlessly across **mobile, tablet, and desktop** devices.  
- UI is clean, vibrant, and accessible to all age groups.

---

## 🛠️ Tech Stack

| Layer       | Technology            |
|-------------|------------------------|
| Structure   | HTML5                 |
| Styling     | CSS3 (Flexbox/Grid)   |
| Logic       | JavaScript (ES6)      |
| Audio       | JavaScript Audio API  |

---

## 🔍 How It Works

1. **Game starts** on page load or when user clicks "Start".
2. **A random color** is added to the sequence and flashes briefly.
3. **Player clicks buttons** to match the full sequence in order.
4. If correct, next level begins (with score incremented).
5. If incorrect, game plays an error sound and **resets**.

---

## 🧪 Challenges Solved

- ✅ Handled **asynchronous playback** of sequences and user input timing.
- ✅ Synced visual and audio feedback using JavaScript event handling.
- ✅ Ensured consistent UX across screen sizes and input speeds.

