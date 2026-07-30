# 🌌 Cosmic Match - Memory Game

A fast, colorful memory-matching game built with plain HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies. Flip cards, find pairs, rack up streak bonuses, and clear the galaxy!


## ✨ Features

- **3 difficulty levels** — Easy (4×3), Medium (4×4), Hard (6×4)
- **Live scoring** with streak bonuses for back-to-back matches
- **Timer** that tracks how fast you clear the board
- **Move counter** to measure efficiency
- **Star rating (⭐⭐⭐)** awarded at the end based on move efficiency
- **Smooth 3D card-flip animations**, shake-on-mismatch, and a glowing pulse on matched pairs
- **Synthesized sound effects** (flip, match, mismatch, win fanfare) generated live with the Web Audio API — no audio files to load
- **Confetti celebration** when you clear all the pairs
- **A bouncy mascot** that reacts to matches and misses
- Fully responsive — works on desktop and mobile
- Mute/unmute toggle for sound

## 🎮 How to play

1. Click any two cards to flip them over.
2. If they match, they stay face-up and you score points.
3. If they don't match, they flip back after a moment.
4. Find all the pairs before you run out of patience — the faster and more accurate you are, the higher your score and star rating!

## 🚀 Getting started

No installation or build tools required.

```bash
git clone https://github.com/binduhasini11/Cosmic-Match.git
cd Cosmic-Match
open index.html
```

You can also serve it locally if you prefer:

```bash
npx serve .
```

Or drag `index.html` straight into any browser tab.

## 🛠️ Tech stack

- **HTML5** for structure
- **CSS3** for animations, gradients, and the 3D card-flip effect
- **Vanilla JavaScript** for game logic, timer, scoring, and a hand-rolled confetti particle system
- **Web Audio API** for all sound effects (synthesized in-browser, no audio assets)

Everything lives in a single self-contained file — easy to drop into any static site or GitHub Pages.

## 📄 License

MIT — free to use, modify, and share.

## 🙌 Contributing

Pull requests are welcome! Ideas for future additions:
- Local best-times / high-score leaderboard
- Two-player turn-based mode
- Alternate icon themes (animals, food, emojis pack swap)
- Light/dark theme toggle
