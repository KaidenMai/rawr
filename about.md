# SmoothDash

Run Geometry Dash at high FPS without the stutter.

## What it does
- **Unlock FPS** – sets your own frame cap (or uncapped with 0).
- **High-precision timer** – asks Windows for a 1 ms timer so frames are evenly spaced. This is the main micro-stutter fix.
- **Disable power throttling** – keeps Windows from moving GD onto slow efficiency cores mid-level.
- **Above-normal priority** (off by default) – helps if background apps cause spikes.
- **Particle amount** – trims particles on heavy levels.

## Tips
- Turn **VSync off** in GD's graphics settings, or your monitor caps you anyway.
- A cap at or slightly above your refresh rate (e.g. 144 → 144–165, 240 → 240) usually feels smoother than uncapped.
- Plug in your laptop and use a High Performance power plan.
