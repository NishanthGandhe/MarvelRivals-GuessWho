# Marvel Rivals: Guess Who? 🎮

A multiplayer web-based "Guess Who?" game featuring all 42 characters from Marvel Rivals! Challenge your friends to guess each other's secret characters in this interactive browser game.

## 🚀 Features

- **Multiplayer**: Play with friends using game IDs
- **Real Character Images**: Official Marvel Rivals character portraits
- **Smart Spell Check**: Fuzzy matching with 30% error tolerance
- **Dual View Modes**: Browse by role (Vanguard/Duelist/Strategist) or alphabetically
- **Marvel Themed**: Custom Marvel font, borders, and styling inspired by rivaldle.com
- **Audio Effects**: Win/lose sound effects using Tone.js
- **Real-time Sync**: Powered by Firebase for instant multiplayer updates

## 🎯 How to Play

1. **Create a Game**: Click "Create New Game" to start
2. **Share Game ID**: Give the generated ID to your friend
3. **Join Game**: Your friend enters the ID and clicks "Join Game"
4. **Select Characters**: Both players secretly choose their mystery characters
5. **Ask Questions**: Take turns asking yes/no questions to eliminate characters
6. **Make Your Guess**: When ready, type a character name to make your final guess
7. **Win**: First to correctly guess the opponent's character wins!

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS + Custom Marvel theme
- **Database**: Firebase Firestore (real-time multiplayer)
- **Authentication**: Firebase Anonymous Auth
- **Audio**: Tone.js for sound effects
- **Images**: Marvel Rivals Wiki + weserv.nl proxy
- **Fonts**: Custom Marvel font

## 🎨 Character Roster

- **10 Vanguards**: Captain America, Doctor Strange, Emma Frost, Groot, Hulk, Magneto, Peni Parker, The Thing, Thor, Venom
- **22 Duelists**: Black Panther, Black Widow, Blade, Hawkeye, Hela, Human Torch, Iron Fist, Iron Man, Magik, Mister Fantastic, Moon Knight, Namor, Phoenix, Psylocke, The Punisher, Scarlet Witch, Squirrel Girl, Spider-Man, Star-Lord, Storm, Winter Soldier, Wolverine
- **9 Strategists**: Adam Warlock, Cloak and Dagger, Invisible Woman, Jeff the Land Shark, Loki, Luna Snow, Mantis, Rocket Raccoon, Ultron

## 🚀 Quick Start

1. Clone the repository
```bash
git clone https://github.com/NishanthGandhe/MarvelRivalsGame.git
cd MarvelRivalsGame
```

2. Open `index.html` in your browser or serve with a local server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

3. Visit `http://localhost:8000` and start playing!

## 🎮 Game Features

### Smart Character Matching
- **Exact matching**: "iron man" → Iron Man
- **Partial matching**: "spider" → Spider-Man  
- **Clean matching**: "blackwidow" → Black Widow
- **Fuzzy matching**: "captian america" → Captain America (handles typos)

### Visual Features
- Character cards flip when eliminated
- Role-based color coding (Yellow for Vanguards, Red for Duelists, Blue for Strategists)
- Responsive grid layout
- Marvel-themed UI with custom borders and fonts

### Multiplayer
- Real-time game state synchronization
- Game ID system for easy friend invites
- Turn-based gameplay with visual indicators
- Automatic error handling and reconnection

## 📱 Browser Support

Works on all modern browsers including Chrome, Firefox, Safari, and Edge. Mobile-friendly responsive design.

## 🤝 Contributing

Feel free to submit issues and pull requests! This is a fun project and improvements are always welcome.

## 📄 License

This project is for educational and entertainment purposes. Marvel characters and assets belong to their respective owners.

---

**Enjoy playing Marvel Rivals: Guess Who? with your friends! 🦸‍♂️🦸‍♀️**
