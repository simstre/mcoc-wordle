# MCOC Wordle

A Wordle-style word guessing game themed around **Marvel Contest of Champions (MCOC)**.

**Play it live:** [mcoc-wordle.vercel.app](https://mcoc-wordle.vercel.app)

## How to Play

Guess the MCOC term in 6 tries. After each guess, tiles change color:

- **Green** — letter is correct and in the right spot
- **Yellow** — letter is in the word but wrong spot
- **Gray** — letter is not in the word

## Features

- **Daily Mode** — one puzzle per day, progress saved
- **Practice Mode** — unlimited random games
- **55+ MCOC words** — game mechanics (PARRY, EVADE, BLEED), champion names (GHOST, BLADE, MAGIK), and game terms (ARENA, NODES, KABAM)
- **Stats tracking** — win %, streaks, and guess distribution
- **MCOC definitions** — learn what each term means after the round
- **Mobile optimized** — fits any screen, works on phones and tablets
- **Marvel themed UI** — dark background with red/gold accents

## Tech Stack

Single HTML file — no build step, no dependencies, no framework. Just HTML, CSS, and vanilla JavaScript.

## Development

```bash
# Serve locally
python3 -m http.server 8300

# Open in browser
open http://localhost:8300
```

## Deployment

Deployed on [Vercel](https://vercel.com) with auto-deploy on push to `main`.
