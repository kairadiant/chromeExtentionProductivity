# Chrome Productivity Extension

A Chrome extension designed to boost productivity by providing a customizable Pomodoro-style timer combined with prioritized task management. Users can reorder tasks, set custom timers, and focus on work sessions with reminders.  

Originally created during QC Code ReSolve.  

---

## 🧰 Features

- **Customizable timer** — Choose different durations for work, short break, and long break intervals.  
- **Task list management** — Create, edit, delete, and reorder tasks; tasks are saved across browser sessions.  
- **Priority ordering** — Tasks can be reordered by priority via drag-and-drop or reindexing.  
- **Notifications & alerts** — Receive browser notifications or audio cues at the end of each period.  
- **Simple UI / UX** — Clean and responsive interface optimized for ease of use within the browser extension context.

---

## 📦 Tech Stack & Architecture

- **Frontend / UI**: HTML, CSS, vanilla JavaScript  
- **Data persistence**: `chrome.storage` APIs (local or sync)  
- **Background scripts**: Timer logic and notification triggers  
- **Popup script**: User interface layer, communicates with background script  
- **Manifest**: `manifest.json` defines extension permissions, scripts, and settings  
