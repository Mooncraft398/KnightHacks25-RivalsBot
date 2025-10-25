# 🎮 Marvel Rivals AI Coach

An AI-powered companion app that **watches your Marvel Rivals gameplay** and gives **real-time coaching commentary** based on your performance — like a personal shoutcaster or in-game mentor!

---

## 🚀 Overview

This desktop app runs **alongside Marvel Rivals** — it doesn’t inject or modify the game.  
It uses **computer vision** to read your HUD (HP, ult status, deaths, etc.), tracks performance stats, and generates short **voice or text commentary** through TTS and OBS overlays.

Built in 36 hours by a 3-person team as a hackathon project 🧠⚡

---

## 🧩 Features (MVP)

✅ Detects your HP and Ultimate status from the screen  
✅ Detects deaths / respawns using color and brightness  
✅ Tracks time since ult ready, deaths per minute, etc.  
✅ Generates real-time coaching lines (rule-based)  
✅ Speaks comments aloud via Text-to-Speech  
✅ Displays on-screen overlay via OBS  

---

## 🛠️ Tech Stack

| Component | Tool |
|------------|------|
| Language | Python 3.11+ |
| Screen Capture | `mss` |
| Computer Vision | `opencv-python` |
| OCR (optional) | `pytesseract` |
| Text-to-Speech | `pyttsx3` |
| Overlay | OBS + Flask or text file watcher |
| Packaging | PyInstaller (for .exe build) |

---

## 🧱 Folder Structure

