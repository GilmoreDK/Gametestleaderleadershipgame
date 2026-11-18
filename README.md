# Project Lead — A Three-Phase Leadership Simulation

A self-contained, browser-based leadership simulation inspired by the publicly
described mechanics of Workz's Playmakers® business simulation (an original work —
not affiliated with, and not copying, Workz). No build step, no dependencies — just
open `index.html`.

## Run it

- Live: https://gilmoredk.github.io/Gametestleaderleadershipgame/ (GitHub Pages, auto-deploys from `main`)
- Locally: open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## The game

You are the new leader of a small project team delivering a client portal in 12
weeks. The game has **three phases**, like the original simulation:

1. **Kickoff** — Hire exactly 3 of 6 team members with your budget. Each member has a
   **personality type** and a core **need**: *clarity*, *motivation*, or *recognition*.
   Then hold the kickoff meeting with the **steering committee** and set shared goals.
2. **The Shift** — Five events, including **unforeseen surprises** (scope doubling, a
   budget cut, an uncredited team member). The project's character changes; goals get
   reformulated. Every choice affects Budget, Morale, Stakeholder trust, Progress —
   and the need meters of team members whose personality matches.
3. **Delivery** — The final review with the steering committee, then your results:
   one of 4 endings based on a leadership score (/400) built from how well you met
   each team member's needs, morale, stakeholder trust, and progress.

Core loop, as in Playmakers: make selections, experience the consequences, recognise
individual traits, meet each member's needs, balance team needs against stakeholder
expectations, and deliver quality on time and on budget.

## Project structure

```
index.html   # the whole game: markup, styles, and game logic in one file
README.md    # this file
```

Tech: vanilla HTML/CSS/JavaScript, all inline in `index.html` (works offline).
GitHub Pages serves it from `main` at the repository root.
