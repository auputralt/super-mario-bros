# Super Mario Bros — Vanilla JS Clone

A complete Super Mario Bros clone by **auputralt**. Built with pure HTML5 Canvas and vanilla JavaScript. No frameworks, no dependencies — just one file. Fully mobile-friendly with touch controls.

## Play

Open `code.html` in any modern browser — works on desktop and mobile.

> Deploy for free: drag the project folder into [Netlify Drop](https://app.netlify.com/drop).

## Features

- **4 Worlds** — 1-1 (overworld), 1-2 (underground), 1-3 (athletic), 1-4 (castle)
- **Full gameplay** — run, jump, double-jump, duck, shoot fireballs
- **Enemies** — Goombas, Koopas, Bowser (boss fight in 1-4)
- **Power-ups** — Super Mushroom, Fire Flower, Star, 1-Up Mushroom
- **Sound** — unique background music per level + SFX (jump, coin, stomp, etc.)
- **Mobile friendly** — responsive canvas + touch D-pad/A/B buttons, auto-detected on mobile devices
- **Save progress** — localStorage persistence
- **All levels unlocked** — pick any world from the start

## Controls

| Action       | Keyboard          | Mobile     |
|-------------|-------------------|------------|
| Move        | Arrow keys / WASD | D-pad      |
| Jump        | Z / Space         | A button   |
| Run / Fire  | Shift / X         | B button   |
| Duck        | Down arrow        | D-pad down |
| Pause       | Escape            | START      |
| Select      | Enter             | START      |

## Tech

- HTML5 Canvas (256×240, scaled up with pixel-perfect rendering)
- Fixed timestep game loop
- Web Audio API for all music and sound effects
- Procedural pixel art sprites (no image assets)
- Zero dependencies

## License

MIT — do whatever you want with it.
