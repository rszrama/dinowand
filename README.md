# Dino Wand

A low-poly first-person browser game: explore a village, shoot your wand, collect coins, and take down dinosaurs — including flying pterodactyls and the Ancient Tyrant.

**Play it here:** https://rszrama.github.io/dinowand/

## How to play

Dinosaurs spawn, alert their pack, and hunt you down. Collect coins from crates and kills, then buy new wands, defensive turrets, and extra hearts. After 25 kills the Ancient Tyrant appears.

Choose **Easy** or **Hard** on the start, death, or victory screen. Shops (the turret keeper, the healer, and the wand shrines) are safe zones — hostiles pause while you buy.

A translucent bar just above the wand / turret buttons shows the direction of hostiles that have spotted you. The center is straight ahead; the ends are almost directly behind you (179° left or right). The scale is tighter in front, so a small move near the center is a smaller angle than the same move near an edge. Each alerted, charging, diving, or attacking dino, raptor, pterodactyl, or the boss gets a dot — wanderers do not. The boss dot is larger and red, pterodactyls are cyan, and closer threats appear brighter and can pulse. The bar stays very faint when nothing is after you.

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
- On phones and tablets, **Play** / **Play Again** goes full screen and locks to landscape (use the **Full** button if you leave full screen). Desktop keeps the usual click-to-lock mouse look and does not go full screen automatically. In portrait, a small banner suggests rotating — you can dismiss it and keep playing
- **iPhone:** Safari can't go full screen in the browser. Open the **Share** sheet and choose **Add to Home Screen**, then launch Dino Wand from that icon — it runs full screen in landscape. Keep the Ring/Silent switch off, or use the home-screen app, so game audio isn't muted

Open `index.html` locally if you prefer — no build step or install. For the home-screen app and full screen, serve it over `https://`.

## Technical notes

Single HTML file using [three.js](https://threejs.org/) r160 from a CDN. All models, sounds, and textures are generated in the page. A small `manifest.json` and icons are included so you can add it to a home screen. Works over `https://` or `file://`.
