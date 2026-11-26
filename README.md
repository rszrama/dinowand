# Dino Wand

A low-poly first-person browser game: explore a village, shoot your wand, collect coins, and take down dinosaurs — including flying pterodactyls and the Ancient Tyrant.

**Play it here:** https://rszrama.github.io/dinowand/

## How to play

Dinosaurs spawn, alert their pack, and hunt you down. Collect coins from crates and kills, then buy new wands, defensive turrets, and extra hearts. After 25 kills the Ancient Tyrant appears.

Choose **Easy** or **Hard** on the start, death, or victory screen. Shops (the turret keeper, the healer, and the wand shrines) are safe zones — hostiles pause while you buy.

## Controls

### Desktop

- **WASD** walk / strafe, **Shift** run, **mouse** look (click to lock the pointer)
- **Click** or hold to shoot your wand
- **1 / 2 / 3** switch wands, **4** place a turret, **E** buy from shrines or shops
- **Esc** or click out of the window to pause

### Mobile / touch

- Left **joystick** to move (diagonals supported); movement always uses run speed. After you press it, that finger keeps steering even if you slide well off the pad — the stick follows so you can reverse quickly
- Drag anywhere else that isn’t a button to look around
- Auto-fires when a hostile is under the crosshair; hold **Fire** to shoot (or place a turret when that slot is active)
- Tap wand / turret slots **1–4**; a **Buy** button appears in shop zones; **Pause** to pause
- Landscape is recommended (still playable in portrait)

Open `index.html` locally if you prefer — no build step or install.

## Technical notes

Single HTML file using [three.js](https://threejs.org/) r160 from a CDN. All models, sounds, and textures are generated in the page (no extra asset fetches besides three.js). Works over `https://` or `file://`.
