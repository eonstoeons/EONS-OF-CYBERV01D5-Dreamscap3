# EONS OF THE CYBERV01D5: DREAMSCAP3

**A collaborative Python creative video game — MIT Open Source**

*The Dream Speaks of Time's Past.*

You awaken in a cyber universe with no memory and little explanation — drifting through the void in a ship that may or may not be yours. What follows is a 5-chapter narrative sequence woven through three fully realized graphics engines, all contained in a single Python file with zero external dependencies.

Now on itch.io - Play in your browser!

https://eons2eons.itch.io/eonsofthecybervoidsdreamscape
---

## What's Inside

**DREAMSCAP3** is a standalone single-file campaign launcher. Run it and you get three things from one file:

**Story Mode** — A 5-chapter narrative sequence with interstitial transmissions. Chapters auto-advance or wait for you depending on type. Progress is saved between sessions.

**Pysplore v4.0** — Unlocked on campaign completion. A full DAW, games suite, and creative tool collection embedded as Chapter 3 of the campaign and accessible independently once earned.

**Free Roam — Omni V01D Engine** — The full open-world sandbox, always available. Three graphics engines that swap automatically based on your mode of travel.

---

## The Campaign

Five chapters, five transmissions, one story.

| # | Title | Engine |
|---|-------|--------|
| 1 | DRIFT | 6-DOF space flight — Void Engine Ultimate |
| 2 | REMNANTS | Infinite ASCII night city drive — Phos City |
| 3 | ARCHIVES | Pysplore v4.0 — DAW · games · tools |
| 4 | INFINITE | Void Engine v2.1 — Confusion Protocol |
| 5 | RELIC | Void Archive Final — 4-mode selector |

GFX chapters (1, 2, 4) auto-advance after 10 minutes. App chapters (3, 5) advance when you close the window. Transmissions advance on ENTER.

---

## Free Roam — Omni V01D Engine

The sandbox mode runs a complete open-world game with three graphics engines that swap automatically:

- **On foot / boarding** → CybervoidFusion DDA raycaster with true look left/right
- **In vehicle** → Phos City Night Drive renderer with procedural windowed buildings
- **In space** → Void Space Sim 6-DOF starfield cosmos

**What you can do:** explore 80 procedurally generated planets across four biomes (Phos City, Void Dungeon, Open Wilds, Moon Surface). Drive abandoned rovers. Launch to space. Board enemy ships. Bring peace to hostile entities with the Peace Emitter. Collect artifact log entries. Recover lost archive shards scattered across the world.

**Two modes:** Peaceful or Combat. Save system with 4 manual slots, autosave, and passcode-based load. In-game stats tracking across session and all-time.

---

## Controls

**On foot / boarding**

| Key | Action |
|-----|--------|
| WASD | Move / strafe |
| Arrow LEFT/RIGHT | Turn |
| Arrow UP/DOWN | Move forward/backward |
| SHIFT | Sprint |
| V | Jump |
| SPACE / LMB | Fire Peace Emitter |
| E | Interact — enter vehicle, terminal, ship |
| F | Take off to space |
| T | Teleport to spaceship |
| L | Open/close artifact log |
| M | Toggle music |
| R | Toggle SFX |
| ENTER | Pause menu |
| ESC | Quit |

**In vehicle**

| Key | Action |
|-----|--------|
| W/S | Throttle / brake |
| A/D | Steer |
| Arrow LEFT/RIGHT | Camera look left/right |
| SHIFT | Boost |
| SPACE | Fire turret |
| E | Exit vehicle |
| F | Take off to space |

**In space**

| Key | Action |
|-----|--------|
| WASD | Pitch / yaw |
| Q/E | Roll |
| Arrow keys | Strafe |
| SPACE | Toggle thrust |
| B | Boost (hold) |
| F | Land on nearby planet |
| G | Board enemy ship |

---

## Known Issues

- X-axis directional controls swap when exiting a vehicle during planetary exploration. Teleport back to space and return to the planet to resolve.
- Peace Emitter laser SFX may disappear after exiting a vehicle. Same fix applies.

---

## Technical

- Pure Python 3 + tkinter — stdlib only
- Zero external dependencies
- Fully offline — works forever without an internet connection
- Single file: everything embedded, no assets to manage
- Procedurally generated graphics, music, and sound effects — all synthesized at runtime from pure math
- Save data stored at `~/.v01d_campaign.json` (campaign) and `~/.omni_void_engine.json` (free roam)

**Requirements:** Python 3 with tkinter. Thonny or PyCharm recommended. Download or copy-paste the file to get started.

---

## Authors

Original concept & code: **eonstoeons**
Co-coded with **Claude (Anthropic)**

GitHub: [github.com/eonstoeons](https://github.com/eonstoeons)

---

## Credits

Other MIT repos and creators that made this possible:

- [irmen/raycaster](https://github.com/irmen/raycaster)
- [Magoninho/raycasting-python](https://github.com/Magoninho/raycasting-python)
- [Piper TTS](https://github.com/rhasspy/piper)
- [s-macke/VoxelSpace](https://github.com/s-macke/VoxelSpace)
- [JayWalker512/ascii_raytracer](https://github.com/JayWalker512/ascii_raytracer)
- [LingDong-/asciimare](https://github.com/LingDong-/asciimare)
- [Dozed12/df-style-worldgen](https://github.com/Dozed12/df-style-worldgen)

---

## License

MIT 2026 · eonstoeons

Modding, tinkering, and personal projects are highly encouraged.

Free, open source, royalty-free. Eons2Eons, Claude, and Anthropic waive all responsibility for use. This is a personal video game project built to explore Python and AI tooling in 2026. Not created for profit. Use responsibly and at your own discretion.

*single-file · pure stdlib · zero deps · offline forever*
