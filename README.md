# NEON SURVIVOR (offline, single-file)

A polished top-down arcade survival shooter that runs as a single `index.html`.

## Features
- Difficulty modes: **Easy / Normal / Hard**
  - scales enemy HP, enemy damage, spawn density, and upgrade rate
- Upgrades triggered by **kill milestones** (threshold grows exponentially)
- **Miniboss** every 5 waves · **Boss** every 10 waves
- Boss clears spawn a **full-heal medkit**
- Customization menu: change **player/enemy/projectile/background/accent** colors
- Pause overlay (“PAUSED”)
- Sound effects (WebAudio synth) + **Mute (M)**

## Run
Open `index.html` in any modern browser.

If your browser blocks local storage in strict modes, run a tiny server:

```bash
python -m http.server 8000
```

Then open: `http://localhost:8000`

## Controls
- Move: WASD / Arrow keys
- Aim: Mouse / touch
- Shoot: Click or Space / touch “FIRE”
- Pause: P
- Restart: R
- Mute: M
- Menu: Esc
