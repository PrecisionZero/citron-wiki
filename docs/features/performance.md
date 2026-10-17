# Performance Features

Citron is designed to combine performance-focused mods with usability improvements. Actual results depend on hardware, drivers, world complexity, render distance, Java runtime, and other software.

## What performance means

- **Average FPS:** how many frames are rendered per second on average.
- **Frame-time consistency:** whether frames arrive evenly; inconsistent frame times can feel stuttery even when average FPS is high.
- **Loading and startup:** time required to initialize the game and enter a world.
- **Memory behavior:** allocation and garbage collection, which can affect pauses.
- **Server or integrated-server behavior:** tick performance in worlds with entities, redstone, or heavy simulation.

## What to expect

No modpack can guarantee a fixed FPS increase on every device. Optimization effects can be small, substantial, or difficult to measure depending on the bottleneck. A graphics-limited system may respond differently from a CPU-limited system.

## Test fairly

1. Use the same Minecraft version, world, location, settings, and Java runtime.
2. Allow the world to settle after loading.
3. Record several captures of equal duration.
4. Compare average FPS and frame-time behavior, not one peak reading.
5. Change one variable at a time and keep a note of the configuration.

Citron's internal development benchmarks are not a promise of user performance. For practical adjustments, see [Performance Settings](../configuration/performance.md).
