<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=36&duration=3000&pause=1000&color=667EEA&center=true&width=700&lines=🚀+100+Days+DSA+Challenge;Track+Every+Day.+Crush+Every+Problem.;Consistency+Beats+Perfection+💪" alt="Typing SVG" />

<br/>

[![GitHub Stars](https://img.shields.io/github/stars/anisha-1811/DSA-TRACKER?style=for-the-badge&color=667eea&logo=github)](https://github.com/anisha-1811/DSA-TRACKER/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/anisha-1811/DSA-TRACKER?style=for-the-badge&color=764ba2&logo=github)](https://github.com/anisha-1811/DSA-TRACKER/network)
[![GitHub Issues](https://img.shields.io/github/issues/anisha-1811/DSA-TRACKER?style=for-the-badge&color=ff4757&logo=github)](https://github.com/anisha-1811/DSA-TRACKER/issues)
[![License: MIT](https://img.shields.io/badge/License-MIT-FFD700?style=for-the-badge)](./LICENSE)
[![HTML5](https://img.shields.io/badge/Built%20With-HTML5%20Only-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)

<br/>

> *"Consistency beats perfection. Every problem you solve makes you stronger! 💪"*

<br/>

[✨ Features](#-features) • [🎮 Live Demo](#-live-demo) • [🚀 Getting Started](#-getting-started) • [📸 Preview](#-preview) • [🤝 Contributing](#-contributing)

---

</div>

## 🎯 What is This?

**100 Days DSA Challenge Tracker** is a beautifully designed, zero-dependency web app that keeps you accountable on your Data Structures & Algorithms journey. Built with **pure HTML, CSS, and JavaScript** — no frameworks, no installs, no build step.

Click a day → mark it done → watch your streak grow. Simple as that.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗓️ **100-Day Calendar Grid** | Visual grid of all 100 days — click any day to toggle complete |
| 📊 **Animated Progress Bar** | Live gradient bar showing your % completion |
| 🔥 **Streak Counter** | Tracks your current consecutive day streak automatically |
| 📈 **Live Stats Panel** | Days completed, current streak, and days remaining — updated instantly |
| 💾 **Auto-Save** | Progress saved to `localStorage` — survives page refresh & closing |
| 🔄 **Reset Button** | Start fresh anytime with a confirmation prompt |
| 📱 **Fully Responsive** | Adapts beautifully on mobile, tablet, and desktop |
| ⚡ **Zero Dependencies** | Pure HTML + CSS + JS — open the file and it just works |

---

## 🎮 Live Demo

> 🌐 **[Try it live here](#)** ← *(Add your GitHub Pages or Netlify link)*

Or just download & double-click `index.html` in your browser!

---

## 📸 Preview

```
┌──────────────────────────────────────────────────┐
│        🚀 100 Days DSA Challenge                 │
│   ████████████████░░░░░░░░░░░░   64%             │
│                                                  │
│  "Consistency beats perfection. 💪"              │
│                                                  │
│  ✓1   ✓2   ✓3   ✓4   ✓5   ✓6   ✓7   ✓8        │
│  ✓9  ✓10  ✓11   12   13   14   15   16          │
│   ...                                            │
│                                                  │
│  64 Completed | 🔥 11 Streak | 36 Remaining      │
│                                                  │
│              [ Reset Challenge ]                 │
└──────────────────────────────────────────────────┘
```

> 💡 Drop a screenshot in your repo and link it here:
> `![Preview](./preview.png)`

---

## 🚀 Getting Started

**No installation needed.** Seriously.

### Option 1 — Clone & Open

```bash
# Clone the repo
git clone https://github.com/anisha-1811/DSA-TRACKER.git

# Navigate into the folder
cd DSA-TRACKER

# Open in browser
# Mac:
open index.html
# Windows:
start index.html
# Linux:
xdg-open index.html
```

### Option 2 — VS Code Live Server

1. Open the folder in **VS Code**
2. Install the **Live Server** extension
3. Right-click `index.html` → **"Open with Live Server"**
4. Done! 🎉

### Option 3 — Deploy Free on GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Set source: `main` branch → `/ (root)`
3. Your tracker goes live at:
   `https://anisha-1811.github.io/DSA-TRACKER/`

---

## 📂 Project Structure

```
DSA-TRACKER/
│
├── 📄 index.html        # The entire app — HTML + CSS + JS in one file
└── 📄 README.md         # You're reading this!
```

> This is an intentional **single-file architecture** — maximum portability, zero setup friction.

---

## ⚙️ How It Works

```
User clicks a day card
        ↓
toggleDay(dayNumber) fires
        ↓
JavaScript Set updated (add/delete)
        ↓
Progress auto-saved to localStorage
        ↓
Calendar grid + Stats re-render instantly
```

- **State** → JavaScript `Set` of completed day numbers
- **Persistence** → `localStorage` key: `dsa-challenge-progress`
- **Streak** → Longest consecutive sequence from Day 1
- **Progress** → `(completedDays / 100) * 100%`

---

## 🗂️ Suggested 100-Day DSA Roadmap

<details>
<summary>📌 Click to expand a day-by-day topic plan</summary>

| Days | Topic |
|---|---|
| 1–10 | Arrays & Strings |
| 11–18 | Linked Lists |
| 19–25 | Stacks & Queues |
| 26–35 | Binary Search & Sorting |
| 36–45 | Trees & Binary Search Trees |
| 46–55 | Heaps & Priority Queues |
| 56–67 | Graphs (BFS, DFS, Dijkstra) |
| 68–80 | Dynamic Programming |
| 81–87 | Recursion & Backtracking |
| 88–92 | Tries |
| 93–97 | Bit Manipulation |
| 98–100 | Mixed Practice & Revision |

</details>

---

## 🤝 Contributing

Contributions are welcome and appreciated! 🙌

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature description"

# 4. Push and open a Pull Request
git push origin feature/your-feature-name
```

### 💡 Ideas for contributions

- 🎨 Multiple color themes / dark mode
- 📝 Add problem name or notes per day
- 📤 Export progress as PNG or PDF
- 🔔 Browser reminder notifications
- 🏆 Milestone badges (25%, 50%, 75%, 100%)

---

## 🐛 Found a Bug?

[Open an issue](https://github.com/anisha-1811/DSA-TRACKER/issues/new) with:
- Steps to reproduce
- Browser & OS info
- Screenshot (if applicable)

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.

---

<div align="center">

## 👩‍💻 Author

**Anisha**

[![GitHub](https://img.shields.io/badge/GitHub-%40anisha--1811-181717?style=for-the-badge&logo=github)](https://github.com/anisha-1811)

---

⭐ **If this tracker helped you stay consistent, drop a star — it means the world!**

<br/>

*Made with 💜, pure HTML, and a lot of ☕ | Happy Coding! 🚀*

</div>
