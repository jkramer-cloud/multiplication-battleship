# Multiplication Battleship — Fleet Command V2

A browser-based battleship-style math game for the Naches Learning Hub. Practice multiplication by selecting a grid coordinate, answering its multiplication fact, and firing at a hidden fleet.

## What's new in V2

- Full graphical ocean/radar board with bright coordinate labels and selected-target reticle
- Distinct, top-down ship hulls and deck details on fleet boards
- Live visual ship-placement previews when hovering or focusing a square
- Animated ocean firing reports for hits, misses, ship losses, and misfires
- On-device synthesized firing, hit, splash, error, and victory sound effects; **Effects On/Off** switch
- Fleet status display and more readable hit/miss graphics
- Responsive layout for desktop, Chromebooks, and phones

## Existing gameplay preserved

- **Vs. Computer** (four computer captains) and **two-player pass-and-play** with privacy screens
- Grid sizes **8×8, 10×10, 12×12, 15×15**; the selected square asks `column × row`
- Math modes: **Training**, **Standard**, **Expert**, and **Nightmare**
- Optional per-answer timer with **regular, 1.5×, 2×, and 3× time allowances**
- Five ships: Carrier, Battleship, Cruiser, Submarine, Patrol boat
- Manual placement, rotate, random placement, restart and end-game features

## GitHub Pages deployment

1. In the existing multiplication Battleship repository, upload or replace the root `index.html` with the `index.html` in this package.
2. Commit the changes and confirm GitHub Pages is publishing the repository root.
3. Open the game from the Learning Hub or repository URL and use `Ctrl + Shift + R` for a hard refresh.

This version is **one self-contained HTML file**, with CSS and JavaScript inside. No extra assets, dependencies, login, or external network calls are required. The browser stores only the optional effects on/off preference; game scores are not permanently saved.

## Accessibility and classroom use

- The audio effects toggle is always available; it defaults to On and can be changed at any time.
- Animations respect the operating system's **Reduce Motion** setting.
- Ship-placement preview works with mouse hover and keyboard focus; the board buttons have accessible labels.
- Optional timed fire is **off by default**, and students can choose additional time when it is enabled.

## Notes

Animated ships and effects are an original arcade-style presentation. This is a math game, not a realistic naval combat simulator.
