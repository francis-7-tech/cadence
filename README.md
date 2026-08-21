# Cadence

A colour and sound memory sequence game built with vanilla JavaScript, jQuery, HTML, and CSS.

Watch the sequence, listen to the cadence, then repeat it back. Each round adds one more step — how far can you go before you slip up?


## Live Demo
Play Cadence - https://cadence-sage-rho.vercel.app/

## How to Play

1. Press any key to start.
2. Watch and listen as a coloured button flashes and plays a sound.
3. Click the buttons in the same order to repeat the sequence.
4. Get it right, and the sequence grows by one more step.
5. Get it wrong, and the game ends — press any key to try again.

## Features

- Progressive sequence generation that grows one step per round
- Audio and visual feedback for both the computer's sequence and the player's input
- Live level tracking displayed in the title
- Game-over state with visual and audio cues, and a clean restart flow

## Tech Stack

- HTML5 & CSS3
- JavaScript (ES6)
- jQuery

## Project Structure

```
Cadence/
├── index.html
├── styles.css
├── game.js
├── sounds/
│   ├── red.mp3
│   ├── blue.mp3
│   ├── green.mp3
│   ├── yellow.mp3
│   └── wrong.mp3
└── README.md
```

## Running Locally

Clone the repo and open `index.html` in your browser — no build step or dependencies to install beyond the jQuery CDN link already included in the HTML.

```bash
git clone https://github.com/francis-7-tech/cadence.git
cd cadence
```

Then open `index.html` directly, or serve it with a local server of your choice.

## Author

Built by [Francis](https://github.com/francis-7-tech).
