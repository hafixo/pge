# pge

Simple looping game engine for Pebble.

## Compatibility with SDK 3.0

This repository will build for both the Aplite and Basalt platforms. If you
are still using SDK 2.9, you should rename `wscript-2.x` to `wscript`.

## Features

- Automatic looping of developer-supplied per-frame logic and rendering.
- 30 frames per second.
- `AppTimer`, `LayerUpdateProc`, `Clicks`, `Window` and `main` abstracted away.
  Implement only your game code.
- `PGESprite` base object to implement game entities.
- Basic collision checking between `PGESprite`s, GRects, lines and points.
- Isometric rendering of rects, boxes and textures.
- Basic game title screen template.
- Simple highscore mechanism.

## Basic Template App

To begin a new game watchapp, begin with the template file in `/docs/`.

## Documentation

[PGE](docs/pge.md) - Main engine documentation.

[PGE Sprite](docs/pge_sprite.md) - Sprite class documentation.

[PGE Title](docs/pge_title.md) - Template title screen documentation.

[PGE Grid](docs/pge_grid.md) - Convenience for grid-based games.

[PGE Splash](docs/pge_splash.md) - Engine splash screen animation documentation.

[PGE Isometric](docs/pge_isometric.md) - Isometric rendering of rects, boxes and textures.

## Features To Do

- Multiplayer?
