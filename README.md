# Keyboard Typing Test

A colorful, animated typing speed test with full QWERTY keyboard visualization, bouncing 3D balls, and fireworks. Built with vanilla HTML, CSS, and JavaScript. Requires a physical keyboard — designed for laptop and desktop screens.

## Features

- **Full QWERTY Keyboard** — visual keyboard highlights keys as you press them (correct = green glow, wrong = red shake)
- **5 Pangram Sentences** — each sentence uses every letter of the alphabet for complete practice
- **3D Animated Balls** — 3 colored balls bounce on correct keypress, shake on wrong, spin on sentence complete
- **Real-time Stats** — WPM, correct keys, wrong keys, accuracy %, streak counter
- **Speed Level Rating** — Beginner → Basic/Acceptable → Average → Good → Professional → Excellent/Advanced
- **Personalized Advice** — encourages reaching 50+ WPM minimum
- **Sound Effects** — distinct sounds for correct keys, wrong keys, sentence completion, and game finish via Web Audio API
- **Fireworks Display** — full-screen fireworks after completing all 5 sentences
- **Progress Bar** — visual sentence-by-sentence progress
- **Sentence Progression** — "Next Sentence →" button after each sentence is complete
- **3D Effects** — perspective-tilted keyboard, glowing neon theme, shadow effects
- **Dark Neon Theme** — designed for laptop/large screens, visually striking

## How to Play

1. Open `index.html` in any modern browser
2. Click **Start Typing!**
3. Type the displayed sentence character by character using your physical keyboard
4. Correct keys glow green, wrong keys glow red
5. Press **Backspace** to fix mistakes
6. After finishing a sentence, click **Next Sentence →**
7. Complete all 5 sentences to see your final stats, speed level, and fireworks

## Speed Levels

| WPM Range | Level |
|-----------|-------|
| Below 20 | Beginner |
| 20–35 | Basic / Acceptable |
| 35–50 | Average |
| 50–70 | Good |
| 70–100 | Professional |
| 100+ | Excellent / Advanced |

## Pangram Sentences

1. A quick brown fox jumps over the lazy dog.
2. The five boxing wizards jump quickly.
3. Sphinx of black quartz, judge my vow.
4. How vexingly quick daft zebras jump!
5. Bright vixens jump; dozy fowl quack.

## Project Structure

```
typing-game/
└── index.html    # Complete game — HTML, CSS, and JS in a single file
```

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — grid/flexbox, animations (keyframes), 3D transforms, custom properties
- **JavaScript (ES5/ES6)** — game logic, keyboard event handling, Web Audio API

## Requirements

- Physical keyboard required (not optimized for mobile touch screens)
- Modern browser — Chrome, Firefox, Safari, Edge

---

**Designed By: Azmat Ali**
