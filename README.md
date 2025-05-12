# Drum-Kit

An interactive drum kit web application built with HTML, CSS, and JavaScript. Play drums using your keyboard or by clicking the buttons!

## About the Project

This project showcases advanced **Document Object Model (DOM)** manipulation and event handling in JavaScript. It creates a virtual drum kit that responds to both mouse clicks and keyboard events, playing corresponding drum sounds and providing visual feedback.

### Implementation Details

- **Event Listeners**: The project uses two types of event listeners:
  - `click` events for mouse interaction
  - `keydown` events for keyboard interaction
- **Audio Control**: Uses the HTML5 `Audio` API to play drum sounds
- **Animation**: Implements CSS animations for button feedback
- **DOM Manipulation**: Dynamically handles user input and updates the UI

### Key DOM Methods Used

```javascript
// Event handling
document.addEventListener();
element.addEventListener();
// Element selection
document.querySelector();
document.querySelectorAll();
// Class manipulation
element.classList.add();
element.classList.remove();
```

## Features

- Interactive drum sounds
- Keyboard support (w, a, s, d, j, k, l keys)
- Visual feedback animation
- High-quality drum samples
- Responsive design for all screen sizes

## How to Play

1. Open `index.html` in your browser
2. Either:
   - Click on the drum buttons with your mouse, or
   - Press the corresponding keys on your keyboard
3. Enjoy the drum sounds with visual feedback!

## File Structure

```
Drum-Kit/
├── index.html      # Main HTML file
├── styles.css      # Styles and animations
├── index.js        # Event handling and sound logic
├── images/         # Drum button images
│   ├── crash.png
│   ├── kick.png
│   ├── snare.png
│   └── tom1-4.png
└── sounds/         # Drum audio files
    ├── crash.mp3
    ├── kick-bass.mp3
    ├── snare.mp3
    └── tom-1-4.mp3
```

## Deployment

This project is ready for deployment on Vercel. All file paths are relative (start with `./`).

---

Created by Charan-Tj.
