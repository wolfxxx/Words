# Wordle Game

A fully-featured, single-file Wordle game implementation with modern UI, statistics tracking, share functionality, and customizable settings.

![Wordle Game](https://img.shields.io/badge/Wordle-Game-green) ![HTML](https://img.shields.io/badge/HTML-5-orange) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow) ![CSS](https://img.shields.io/badge/CSS-3-blue)

## 🎮 Features

### Core Gameplay
- **Classic Wordle Mechanics**: Guess 5-letter words in 6 attempts
- **Real-time Dictionary Validation**: Uses the Free Dictionary API to validate words
- **Visual Feedback**: Color-coded tiles (🟩 Green = correct, 🟨 Yellow = present, ⬛ Gray = absent)
- **Smooth Animations**: Tile flips, pop effects, and confetti celebrations

### Statistics & Tracking
- **Game Statistics**: Track games played, win percentage, current streak, and max streak
- **Guess Distribution**: Visual chart showing your guess pattern distribution
- **Local Storage**: All stats persist between sessions

### Social Features
- **Share Results**: Generate emoji grid to share your results
- **Copy to Clipboard**: One-click copy of your game results
- **Native Share API**: Uses device's native share functionality when available

### Customization
- **Dark/Light Theme**: Toggle between dark and light modes
- **Hard Mode**: Enable to force using all revealed hints in subsequent guesses
- **Settings Persistence**: All preferences saved automatically

### User Experience
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Keyboard Support**: Full keyboard navigation with Enter, Backspace, and letter keys
- **Accessibility**: Focus states and keyboard-friendly navigation
- **Help Section**: Built-in instructions with visual examples

## 🚀 Getting Started

### Installation

No installation required! Just open `index.html` in any modern web browser.

1. **Download the file**:
   ```bash
   git clone https://github.com/wolfxxx/Words.git
   cd Words
   ```

2. **Open in browser**:
   - Simply double-click `index.html`
   - Or open it from your browser's File menu

### Usage

1. **Start Playing**: Open `index.html` and start guessing 5-letter words
2. **Enter Words**: Type letters or click the on-screen keyboard
3. **Submit Guess**: Press Enter or click the ENTER button
4. **View Stats**: Click the 📊 icon in the header to see your statistics
5. **Customize**: Click the ⚙️ icon to access settings

## 📖 How to Play

1. **Guess the Word**: Type a 5-letter word and press Enter
2. **Interpret Colors**:
   - 🟩 **Green**: Letter is correct and in the right position
   - 🟨 **Yellow**: Letter is in the word but wrong position
   - ⬛ **Gray**: Letter is not in the word
3. **Win or Lose**: You have 6 attempts to guess the correct word

### Hard Mode

When enabled, Hard Mode requires you to use:
- All correct letters (green) from previous guesses
- All revealed letters (yellow) from previous guesses

This makes the game more challenging and strategic!

## 🎨 Features Breakdown

### Statistics Dashboard
- **Games Played**: Total number of games completed
- **Win Percentage**: Percentage of games won
- **Current Streak**: Consecutive wins in a row
- **Max Streak**: Longest winning streak achieved
- **Guess Distribution**: Bar chart showing frequency of wins by guess count

### Share Functionality
After completing a game, you can share your results as an emoji grid:
```
Wordle 3/6

🟩⬛⬛⬛⬛
🟩🟨⬛⬛⬛
🟩🟩🟩🟩🟩
```

### Settings Options
- **Dark Mode**: Toggle between dark and light themes
- **Hard Mode**: Enable more challenging gameplay
- **Reset Statistics**: Clear all saved statistics (with confirmation)

## 🛠️ Technology

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS custom properties for theming
- **Vanilla JavaScript**: No dependencies or frameworks
- **Free Dictionary API**: For word validation
- **LocalStorage**: For persistent data storage

## 📱 Browser Support

Works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## 🎯 Features in Detail

### Animations
- **Tile Flip**: Smooth 3D flip animation when revealing letter status
- **Pop Effect**: Subtle scale animation when typing letters
- **Shake**: Row shake animation for invalid words
- **Confetti**: Celebration animation on winning

### Visual Enhancements
- **Glow Effects**: Subtle glow on correct tiles
- **Smooth Transitions**: All state changes are animated
- **Modal Animations**: Slide-up and fade-in effects
- **Loading States**: Visual feedback during API calls

## 📝 Game Rules

- Each guess must be a valid 5-letter English word
- Words are validated against an online dictionary
- You have exactly 6 attempts
- Letters can appear multiple times in the word
- Case doesn't matter (automatically converted)

## 🔧 Customization

All game settings are stored in localStorage:
- Theme preference
- Hard mode setting
- Statistics data

To clear all data, use the Reset Statistics button in Settings.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available for personal use.

## 🙏 Acknowledgments

- Wordle game concept by Josh Wardle
- Free Dictionary API for word validation
- Inspired by the original NYT Wordle

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Enjoy playing Wordle!** 🎉
