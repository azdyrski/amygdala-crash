# Nanaca Crash (HTML5)

A Phaser 3 port of the Flash game Nanaca Crash. Logic is ported from the decompiled ActionScript in `import/`; art and music are in `assets/`.

## Run
Serve the folder statically, e.g. `python3 -m http.server 8000`, then open http://localhost:8000.

## Play
Click to lock the angle, hold for power, release to launch. Crash into characters to get boosted, click on the SPECIAL prompt for bigger boosts, and click mid-air (height 3-10) for Nanaka's kick.

## Layout
- `src/game/GameControl.js` – physics and power-up logic
- `src/game/characters.js` – character data and hit handlers
- `src/scenes/` – Boot, Title and Game scenes
- `src/data/assets.js` – asset list (image names were mapped by eye from `import/images`)
