# Speedrun Timer

> On-screen timers for live run timing.

Part of the [Speedrun modpack](https://github.com/h2pack-speedrun/speedrun-modpack).

## What It Does

Speedrun Timer displays timing overlays during runs so you can track attempt pace without leaving the game.

The live timer stack includes:

- `RTA`
  Real-Time Attack, based on wall-clock time.
- `LRT`
  Load-Removed Time, which subtracts load time from the run timer.
- `IGT`
  In-Game Time support through the engine timer layer.

In normal use, the module draws the active run timers on screen and keeps the load-removed timer in sync with map-load timer blocks.

Use it when you want a built-in speedrun timing overlay instead of relying on external timing alone.

## Installation

Install via [r2modman](https://thunderstore.io/c/hades-ii/) or manually place in your `ReturnOfModding/plugins` folder.

This module is usually installed as part of the full [Speedrun modpack](https://github.com/h2pack-speedrun/speedrun-modpack), where it appears in the shared Speedrun UI with the other speedrun-focused modules.
