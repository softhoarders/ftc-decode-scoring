# FTC DECODE Scorer · 2025–2026

A **fast, touchscreen-friendly scoring interface** for the **FIRST Tech Challenge (FTC) DECODE 2025–2026 game**.

This app is designed for **live match scoring**, allowing referees or scorekeepers to quickly track artifacts, bonuses, and match results for both alliances.

The UI is optimized for **tablets and touchscreens**, with large buttons, neon visual feedback, and a built-in match timer.

---

# ✨ Features

## ⏱ Match Timer

* Full match timer with **automatic phase indicators**
* Visual warnings when time is low
* Start / stop control
* Phase badge display

---

## 🔴🔵 Dual Alliance Scoring

Two independent panels for:

* **Red Alliance**
* **Blue Alliance**

Each panel includes:

* Artifact scoring buttons
* Counters for scoring elements
* Toggleable bonuses
* Base / placement options
* Running subtotal display

---

## 🧩 Artifact Tracking

Quick buttons for tracking artifacts such as:

* Green artifacts
* Purple artifacts
* Other scoring elements depending on game rules

Artifacts are displayed visually in a **sequence timeline** so referees can review scoring order.

---

## 🧮 Automatic Score Calculation

The app automatically calculates:

* Autonomous points
* Tele-op points
* Endgame points
* Total alliance score

Scores update instantly as actions are recorded.

---

## 📜 Match History

Every match result is automatically stored locally.

Features include:

* Scrollable match history
* Winner display (Red / Blue / Tie)
* Expandable match details
* Delete individual matches

Useful for reviewing scoring after a match.

---

## 📱 Mobile / Tablet Optimized

* Designed primarily for **landscape tablet use**
* Built-in **orientation warning overlay**
* Large touch targets
* Minimal scrolling

Perfect for **Driver Hub tablets, Android tablets, or iPads**.

---

## 📦 PWA Support

The app includes **Progressive Web App (PWA)** features.

This allows:

* Installing the scorer like a native app
* Offline usage
* Quick launch from the home screen

When supported, a banner will appear prompting installation.

---

# 🚀 Usage

1. Open `index.html` in any modern browser.

2. Start a match:

   * Enter match details (if applicable)
   * Press **START**

3. During the match:

   * Tap buttons to record scoring events
   * Toggle bonuses when achieved
   * Track artifacts in real time

4. After the match:

   * Final score is displayed
   * Match is saved to **History**

---

# 🖥 Running the App

Because it is a **single-file web app**, it can run in multiple ways:

### Option 1 — Open Directly

```
open index.html
```

### Option 2 — Run a Local Server (recommended)

```
python3 -m http.server
```

Then open:

```
http://localhost:8000
```

---

# 📂 Project Structure

```
.
├── index.html     # Entire scoring app (HTML + CSS + JS)
└── README.md
```

The project is intentionally **single-file** for easy deployment.

---

# 🎨 UI Design

The interface uses a **cyber-neon scoreboard style** inspired by:

* Esports overlays
* Sci-fi HUD interfaces
* Robotics competition scoreboards

Fonts used:

* Orbitron
* Share Tech Mono
* Inter

---

# 🧠 Design Goals

* Extremely **fast input during matches**
* **Clear scoring feedback**
* **Minimal referee confusion**
* Fully **offline capable**

---

# 📜 License

Free to use and modify for FTC teams, competitions, or practice matches.

---

# 🤖 Built For

**FIRST Tech Challenge – DECODE Season 2025–2026**

Designed for teams who want a **cleaner, faster manual scoring interface** during testing or scrimmages.
