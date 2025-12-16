# ⏰ Clock UI Design

A modern **digital clock UI** built with **HTML, CSS, and JavaScript**. Displays hours, minutes, seconds, and AM/PM in a stylish, colorful layout.

---

## 🎮 Features

- Real-time digital clock
- Displays **hours, minutes, seconds**, and AM/PM
- Stylish gradient-colored blocks for each time unit
- Reflective effect below numbers
- Fully responsive design
- Lightweight and easy to integrate into any webpage

---

## 🛠 Installation / Play Locally

1. Clone or download the repository.
2. Open `index.html` in a modern web browser (Chrome, Firefox, Edge, Safari).
3. The clock will start automatically.

---

## 📂 Project Structure


---

## ⏱ How it Works

- JavaScript gets the **current time** using `new Date()`.
- Updates the DOM elements every second using `setInterval`.
- Converts 24-hour format to **12-hour format** with AM/PM.
- Adds leading zeros for hours, minutes, and seconds less than 10.
- CSS applies gradients, shadows, and reflective effects for a modern look.

---

## 🎨 Styling

- **Colors:** Bright blue for hours/minutes, pink for seconds
- **Layout:** Horizontal blocks for each time unit
- **Fonts:** Open Sans for clean readability
- **Effects:** Reflections below time blocks using `-webkit-box-reflect`

---

## 🔧 Scripts Overview

- Inline JS in `index.html`
  - `clock()` function updates time every second
  - Handles 12-hour conversion and AM/PM display
  - Updates HTML content for hours, minutes, seconds, and AM/PM

---

## ⚡ How to Extend

- Add **custom themes** or color schemes
- Implement **alarms** or countdown timers
- Animate seconds or minutes for smoother transitions
- Add **date display** below the clock
- Make it **interactive** (click to change themes)

---

## 📝 Credits

- **Developer:** Engineer Erfan Aminnezhad
