# Sheru Bhai — 3D Open World

A browser-based 3D action-game prototype built with Three.js.

## Play locally
Because the game uses JavaScript modules, serve this folder over HTTP (do not open index.html as a file).

```bash
python -m http.server 8000
```

Open http://localhost:8000

## GitHub Pages
1. Open repository Settings → Pages.
2. Under Build and deployment, choose Deploy from a branch.
3. Select branch `main` and folder `/ (root)`, then Save.
4. Wait for the Pages deployment. The game URL will be shown in Settings → Pages.

## Controls
- WASD: move
- Shift: sprint
- Space: jump
- F: punch nearby rivals
- E: collect nearby legend cards
- Drag mouse: rotate camera
- Touch: on-screen joystick and action buttons

## Included prototype systems
- Third-person 3D full-body player character
- Procedural city blocks, roads, trees and buildings
- Rival NPCs that approach and attack
- Melee combat, health and stamina
- Collectible legend cards and coins
- Mission progress and responsive mobile controls

## Notes
This is a playable foundation, not a finished AAA photorealistic game. Three.js is loaded from jsDelivr, so the first load requires internet access. Character art, animation rigs, sound, save accounts, multiplayer servers and optimized authored world assets are future production stages. All currency is fictional and has no real-money value.
