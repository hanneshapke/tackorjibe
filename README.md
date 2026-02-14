# Right of Way — Sailing Rules Trainer

An interactive browser-based game that teaches sailing right-of-way rules through visual scenarios. Pick the boat with right of way and learn why.

## How It Works

The game presents 15 progressively harder scenarios across 4 levels:

1. **Basics** (Q1–5) — Port/starboard tack encounters between two boats
2. **Same Tack** (Q6–9) — Windward/leeward situations where both boats share a tack
3. **Advanced** (Q10–13) — Overtaking rules and wind shadow scenarios
4. **Multi-Boat** (Q14–15) — Three boats converging with mixed tacks

Each scenario renders an animated canvas showing boats on the water with wind direction, sail positions, heading arrows, and (when relevant) wind shadow cones. You choose which boat has right of way and receive an explanation of the applicable rule.

## Rules Covered

- **Port gives way to Starboard** — the fundamental opposite-tack rule
- **Windward boat keeps clear** — same-tack leeward boat has right of way
- **Overtaking boat keeps clear** — boat ahead has right of way regardless of tack
- **Wind shadow** — upwind boat blanketing a leeward boat must keep clear

## Scoring

- Points scale with level difficulty (10 points x level number)
- Streak bonuses reward consecutive correct answers
- Final stats show correct/wrong counts and best streak

## Running

Open `index.html` in any modern browser. No build step or dependencies required — everything (HTML, CSS, JS) is in a single file.
