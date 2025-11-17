# CurlOS Game Center

A modern, feature-rich game center built with pure HTML, CSS, and JavaScript.

## Features

### Game Center Dashboard
- Beautiful gradient UI design
- Statistics tracking (games available, time played, high score)
- Game card with hover effects
- Responsive design for mobile and desktop

### Settings Menu
Comprehensive settings panel with multiple categories:

#### Audio Settings
- Sound Effects toggle
- Background Music toggle
- Volume slider (0-100)

#### Display Settings
- Theme selector (Default, Dark Mode, Retro)
- Animations toggle

#### Gameplay Settings
- Difficulty selector (Easy, Normal, Hard, Expert)
- Auto-Save toggle

#### Data Management
- Reset Statistics button

### Data Persistence
- All settings saved to localStorage
- Play time tracking
- High score tracking
- Settings persist across sessions

## Games

### Heavy Defence
A strategic tower defense game where you defend your castle from waves of enemies.

## Structure

```
curlOS/
├── index.html          # Game Center main page
├── games/
│   └── heavy-defence/
│       └── index.html  # Heavy Defence game
└── README.md           # This file
```

## Usage

1. Open `index.html` in a web browser
2. Click on the Heavy Defence card to play
3. Access settings via the "Settings" button in the header
4. All progress is automatically saved

## Technical Details

- Pure vanilla JavaScript (no frameworks)
- localStorage for data persistence
- Responsive CSS Grid layout
- Smooth animations and transitions
- Modal-based settings interface

## Browser Support

Works on all modern browsers that support:
- ES6 JavaScript
- CSS Grid
- localStorage API
- HTML5

---

Built with ❤️ for gamers
