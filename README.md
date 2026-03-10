# Mars Colony — PARTH ANAND

A browser-based Mars colony survival simulator built for the Hack Club Challenger Space Mission (March 2026).

---

## What is this?

You're a colony commander on Mars. Your job is to keep your colonists alive and grow the population from 4 to 100 before everything falls apart. You manage oxygen, food, power, iron, and crystal  while dealing with dust storms, crop blights, radiation spikes, and random events that keep things unpredictable.

It's a resource management + base-building game that runs entirely in the browser. No installs, no setup, just open the file and play.

---

## How to play

1. open the website in your browser
2. Hit **Launch Mission**
3. Select a building from the left panel, then click an empty cell on the colony grid to place it
4. Use **Next Sol** to advance time, or set a speed (1x / 2x / 3x) for auto-simulation
5. Manage your resources — if oxygen or food hits zero, colonists start dying
6. Research new technologies to unlock advanced buildings
7. Reach 100 colonists to win

---

## Buildings

| Building | What it does |
|---|---|
| Habitat | Houses 4 colonists |
| O₂ Generator | Produces oxygen each sol |
| Greenhouse | Grows food |
| Solar Array | Generates power |
| Iron Mine | Extracts iron ore |
| Crystal Drill | Mines rare crystals |
| Research Lab | Produces science points |
| Med Bay | Improves colonist health |
| Water Extractor | Melts ice for O₂ and food bonus |
| Comms Array | Boosts morale and science |
| Nuclear Reactor | Requires research — high power output |
| Great Dome | Requires research — large housing + morale |

---

## Why is it one single HTML file?

I kept everything (HTML, CSS, JavaScript) in one file on purpose. The main reason is portability — anyone can download it, double-click it, and it just works. No npm, no build tools, no server, no dependencies to install. For a Hack Club project where the goal is to ship something and show it off, a single file is the cleanest way to do that. You can share it on GitHub, email it, put it on a USB drive, anything. It also made development faster since I didn't have to set up a project structure just to build a game.

---

## Tech used

- HTML5 Canvas (starfield animation)
- Vanilla JavaScript (all game logic)
- CSS3 (animations, layout, UI)
- Google Fonts (Orbitron, Share Tech Mono, Exo 2)

No frameworks. No libraries. Just browser APIs.

---

## AI usage

I used Claude as a debugging tool while building this — mostly to catch logic errors in the resource calculations and fix layout issues I was running into. The game concept, mechanics, and design decisions are my own. Claude helped me spot bugs faster than I would have on my own, which I think is a fair and honest way to use it.

---

## Submitted to

Hack Club Challenger Space Mission

---

Built by Parth / Prime Studios
