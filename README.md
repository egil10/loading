# Loading Lab

A collection of five interactive loading screen experiments — cursor-driven, scroll-aware, and built purely with HTML5 Canvas + CSS. Inspired by the kinetic web experiences of AI startups and experimental sites.

**[→ Live demo](https://egil10.github.io/loading/)**

---

## Screens

| # | Name | Concept |
|---|------|---------|
| 01 | **Gravity** | ~680 white particles spell LOADING. Your cursor acts as a gravitational well — pull them in, watch them snap back. |
| 02 | **Aurora** | Deep-space glowing blobs drift with `screen` blending. A mouse-chasing orb trails your cursor through a purple nebula. |
| 03 | **Terminal** | Matrix rain behind a glitch-text panel. Progress bar and status lines tick up fresh each visit. |
| 04 | **Neural** | Particle mesh where your cursor repels nodes. Edges light up as your cursor sweeps through them. |
| 05 | **Kinetic** | Bold 900-weight typography. Every letter warps in vertical position, scale, and rotation based on cursor X/Y. |

---

## Navigation

- Click `01` – `05` in the floating nav bar
- Press `1` – `5` on the keyboard
- `←` `→` arrow keys to cycle through screens

---

## Stack

- Vanilla HTML / CSS / JavaScript — no dependencies, no build step
- HTML5 Canvas for all particle and rain animations
- CSS `backdrop-filter` + `mix-blend-mode: difference` for the nav and cursor
- Google Fonts: [Inter](https://fonts.google.com/specimen/Inter) + [Space Mono](https://fonts.google.com/specimen/Space+Mono)

---

## Run locally

Just open `index.html` in a browser — no server needed.

```bash
git clone https://github.com/egil10/loading.git
cd loading
open index.html   # or double-click it
```
