# Day 20 – Face Puzzle Game using Claude AI

## 🎯 Objective

The objective of this task was to use Claude AI to generate a fully functional Face Puzzle Game as a single self-contained HTML application. The application captures a user's photo using the webcam, converts it into a puzzle, and provides an interactive gaming experience with timers, move tracking, and a leaderboard.

---

## 🎮 Project Overview

The Face Puzzle Game is an interactive web application that allows users to:

- Capture a photo using the webcam.
- Convert the captured image into a puzzle.
- Select different puzzle difficulty levels.
- Solve the puzzle using drag-and-drop or touch controls.
- Track completion time and moves.
- Save best scores using browser local storage.

---

## ✨ Features Implemented

### 📷 Camera Access

- Webcam access using `getUserMedia()`
- Live camera preview
- Capture image using the **Take Photo** button
- Graceful handling of camera permission denial

---

### 🧩 Puzzle Generation

- Image sliced into puzzle pieces
- Difficulty Levels:
  - 3 × 3
  - 4 × 4
  - 5 × 5
- Randomized but solvable puzzle generation
- Interactive draggable puzzle pieces

---

### 🖱️ Drag & Touch Controls

- Mouse drag-and-drop support
- Touch gesture support for mobile devices
- Piece swapping functionality
- Snap-to-grid placement
- Highlight active piece while dragging
- Green border indication for correctly placed pieces

---

### ⏱️ Timer & Move Counter

- Live timer in **mm:ss.t** format
- Automatic timer start when the puzzle begins
- Move counter
- Correct pieces counter
- Real-time progress tracking

---

### 🏆 Win Detection & Leaderboard

- Automatic puzzle completion detection
- Results popup showing:
  - Final Time
  - Total Moves
  - Puzzle Difficulty
- Top 5 scores saved using **Local Storage**
- Persistent leaderboard displaying:
  - Date
  - Time
  - Moves
  - Difficulty

---

### 🎨 User Interface

- Modern and responsive design
- Desktop and mobile friendly
- Retake Photo option
- Play Again button
- New Photo button
- Clean dashboard layout
- Interactive animations and smooth transitions

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas API
- MediaDevices API (`getUserMedia`)
- Local Storage API

---

## 📚 Key Learnings

- Learned how to access webcam functionality using the MediaDevices API.
- Understood image capture and manipulation using the Canvas API.
- Explored puzzle generation algorithms using image slicing techniques.
- Implemented drag-and-drop interactions for desktop and touch devices.
- Learned how to store and retrieve leaderboard data using Local Storage.
- Improved understanding of responsive UI design and browser compatibility.

---

## 📸 Screenshots Included

- Camera Preview
- Captured Photo
- Difficulty Selection
- Puzzle Gameplay
- Timer & Move Counter
- Puzzle Completion Screen
- Leaderboard

---

## 💡 Biggest Takeaway

This project demonstrated how modern web technologies can be combined to create an engaging browser-based game without relying on external frameworks. 
Integrating webcam access, image processing, puzzle logic, drag-and-drop functionality, timers, and persistent leaderboards showcased the capabilities of HTML, CSS, and JavaScript in building interactive web applications.

---

## 📂 Files Included

- face-puzzle-game.html
- day20.md
- Camera Preview Screenshot
- Captured Face Screenshot
- Puzzle Gameplay Screenshot
- Results Screen Screenshot
- Leaderboard Screenshot


---

## ✅ Conclusion

Day 20 provided practical experience in building an interactive Face Puzzle Game using Claude AI. 
The project combined webcam integration, image processing, responsive design, game mechanics, and browser storage into a single self-contained HTML application. It highlighted how AI-assisted development can accelerate the creation of engaging, feature-rich web applications while strengthening front-end development skills.
