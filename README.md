# Lead On — A Leadership Game in Three Phases

A simple, self-contained story/choice-based leadership game that runs entirely in the
browser. No build step, no dependencies — just open `index.html`.

## Run it

Open `index.html` in any modern browser, or serve the folder locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## How to play

The game has three phases:

1. **Assemble** — You start with 100 gold. Recruit exactly 3 companions from a roster of
   6. Each companion has a role (Strategist, Diplomat, Vanguard, Scout, Medic, Engineer)
   that unlocks special dialogue options later, plus a small stat bonus.
2. **Lead** — Face 5 crises. Every choice changes your **Morale**, **Trust**,
   **Reputation**, and sometimes your **Gold**. Some choices are only available if you
   recruited the right role in Phase 1.
3. **Legacy** — Make one final decision, then receive your ending and leadership score
   (Morale + Trust + Reputation, out of 300). There are 4 possible endings.

## Project structure

```
index.html   # the whole game: markup, styles, and game logic in one file
README.md    # this file
```

Tech: vanilla HTML/CSS/JavaScript. Everything is inline in `index.html`, so the game
also works offline by double-clicking the file.
