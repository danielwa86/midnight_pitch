# midnight_pitch

**A physics based isometric football match simulation**

`midnight_pitch` is a small browser-based football match simulation (built with Three.js) with an isometric view and ball physics and more

## Play

```text
https://danielwa86.github.io/midnight_pitch/
```

## Project files

```text
midnight_pitch/
├─ index.html
├─ match_engine_config.js
└─ README.md
```

## Features

- Relaxing AI-controlled football match simulation
- Isometric view and smooth camera controls
- Kick the ball yourself and become the The hand of God!
- Physics-based ball movement, bounces, shots, passes, saves, and dribbles
- Goal celebrations and "cinematic" replay system
- Endless mode, just one more game
- Randomized European-style teams, kit colors, player names, and player attributes
- Random weather and time-of-day presets (Rain, snow, mist, fog, floodlit night, evening, day, and cloudy atmospheres)
- Multiple camera views (placeholder)
- Match result log with copy/save export

## Controls

| Control | Action |
| --- | --- |
| Mouse wheel | Smooth zoom |
| Right mouse drag | Pan camera |
| Middle mouse drag | Rotate camera in isometric mode |

## Menus and known issues

- Most menus are barebones or placeholder right now, but still work (try the manager cam)
- Sometimes 2 players can get stuck in the same position before throw-in or corner, won't reset until half time or match end
- Replays might cut off objects on aggressive angles

## Configuration

Most tuning values are in:

```text
match_engine_config.js
```

You can adjust things like:

- match speed
- ball physics
- player movement
- goalkeeper behavior
- shot/cross/corner behavior
- replay camera behavior
- weather presets
- fog and particle strength
- team randomization
- kit colors
- UI defaults
- audio defaults

After editing the config, refresh the browser page.

## Notes

This is just a just for fun project made with AI and Inspired by Black & White, Football Manager and Project Zomboid.

## License

MIT
