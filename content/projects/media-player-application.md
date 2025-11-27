---
title: "Media Player Desktop Application"
summary: "A YouTube-inspired desktop media player with smart HUD behavior, keyboard shortcuts, and smooth audio/video playback, built with Java and JavaFX."
dateString: 2022
draft: false
tags: ["Java", "JavaFX", "FXML", "Maven", "Media Player", "Desktop App", "Windows", "macOS", "Linux"]
showToc: false
weight: 207
cover:
    image: "projects/Media-Player.jpg"
--- 

### 🔗 [GitHub Repo – Desktop Media Player](https://github.com/Rayan-Mansoor/Media-Player-Java-FXML)

## Description

A lightweight, **YouTube-style desktop media player** for both audio and video, built with **Java**, **JavaFX**, and **Maven**.

The focus of this project was to make playback feel “right”:

- Smooth, predictable seeking
- Keyboard shortcuts that always work
- A HUD that auto-hides when you’re just watching
- Safe file handling and clear feedback

It runs as a cross-platform desktop app on **Windows, macOS, and Linux**.

---

## Key Features

- **Smooth Playback Controls**  
  Play, pause, and stop with one tap or via keyboard. Seeking is clamped and predictable (`±10s` jumps), and when media ends it cleanly resets to `00:00`.

- **Scrub Preview & Safe Seeking**  
  While dragging the progress slider you see a **preview time**, and the player only seeks when you release, avoiding accidental jumps.

- **Playback Speed Options**  
  Built-in rate controls (e.g. **0.5×, 0.75×, 1×, 2×**) so users can slow down or speed up content easily.

- **Volume, Mute & Keyboard Nudges**  
  Volume slider with real-time updates, keyboard nudges (±5%), and instant mute/unmute with icon feedback.

- **YouTube-Like HUD Behavior**  
  The control HUD **auto-hides** after inactivity and reappears on any mouse movement or key press, keeping the video area clean while still feeling responsive.

- **Keyboard & Mouse Shortcuts**  
  Global shortcuts handled at the scene level so they work even when controls have focus:  
  `Space` (play/pause) · `←/→` (−/+10s) · `↑/↓` (volume ±5%) · `M` (mute) · `F` (full screen) · double-click video (play/pause).

- **Robust File Handling**  
  Cancel-safe file chooser (no crashes if the dialog is closed), reuses the **last opened folder**, and disposes previous media players before loading new files.

- **Responsive Video Layout**  
  The video view resizes with the window and keeps overlay icons centered over the actual video region for a polished feel.

---

## Tech Stack

- **Language:** Java (JDK 17+)  
- **UI:** JavaFX (controls + FXML)  
- **Build & Dependencies:** Maven  
- **Styling:** JavaFX CSS for HUD and controls  
- **Target Platforms:** Windows, macOS, Linux (cross-platform desktop)