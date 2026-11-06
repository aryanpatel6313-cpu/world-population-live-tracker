# 🌍 GlobalPulse | Real-Time World Population & Vital Statistics Dashboard

A high-performance demographic intelligence platform simulating live global vitals, real-time births/deaths, interactive world political atlas, 50-country state/city demographics, and neural AI advisory.

---

## ✨ Features

- **⚡ Real-Time Vital Clocks:** Live simulation of world population (8.25B+), births today, deaths today, and net population growth per second.
- **🗺️ Interactive World Atlas Map:** Powered by Leaflet.js with authentic National Geographic pastel styling, interactive country polygons, pulsing megacity markers, and ISS real-time satellite orbital tracker.
- **🏛️ 50-Nation Administrative Explorer:** Complete demographic breakdown of states, union territories, provinces, and major cities across 50 countries (population, national share %, capital, density, literacy, TFR).
- **🤖 GlobalPulse Master AI Advisor v3.0:** Instant demographic intelligence briefing, voice Q&A, and head-to-head country demographic battle comparisons.
- **📊 Real-Time Analytics & Projections:** Live population growth trajectories, continent breakdown donuts, top 10 nations bar charts, and UN 2100 demographic time-travel projections.
- **🚀 100% Offline Standalone Styling:** Complete local Tailwind CSS engine with glassmorphic dark theme (`#020617`), zero external styling dependencies.
- **💾 SQLite Backend:** Node.js + Express backend with persistent SQLite storage for real-time counters and demographic datasets.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, Modern JavaScript (ES6+), Standalone Local Tailwind CSS, Chart.js, Leaflet.js
- **Backend:** Node.js, Express.js
- **Database:** SQLite3 (`population.db`)
- **Map:** Leaflet Tile Engine + GeoJSON World Polygons + TopoJSON

---

## 🚀 Getting Started

### 1. Prerequisites
- Node.js (v16 or higher)
- npm

### 2. Installation
```bash
# Clone the repository
git clone https://github.com/aryanpatel6313-cpu/world-population-live-tracker.git

# Navigate to project directory
cd world-population-live-tracker

# Install backend dependencies
npm install
```

### 3. Running the Dashboard
```bash
# Start backend server
npm start
```
The server will start at:
👉 **`http://localhost:3000`**

Open `http://localhost:3000` in any web browser. You can also directly open `3.html` in your browser.

---

## 📂 Project Structure

```text
├── server.js              # Express API & SQLite database engine
├── population.db          # SQLite persistent database
├── package.json           # Dependencies and startup scripts
├── tailwind.css           # Local standalone CSS system
├── 3.html                 # Standalone root dashboard
├── public/
│   ├── index.html         # Main dashboard interface
│   ├── 3.html             # Mirror static dashboard
│   └── tailwind.css       # Standalone stylesheet
└── README.md              # Project documentation
```

---

## 👤 Author

- **Aryan Patel** - [@aryanpatel6313-cpu](https://github.com/aryanpatel6313-cpu)
