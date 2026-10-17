# Performance Settings

There is no universal setting combination for every computer. Start with moderate values and adjust based on the bottleneck you observe.

## Suggested tuning order

1. Lower **render distance** if GPU or CPU load is high.
2. Lower **simulation distance** if world ticking or entity processing is the bottleneck.
3. Reduce shader quality or disable shaders to test GPU load.
4. Reduce particles and expensive visual effects if frame times improve when they are disabled.
5. Close unnecessary background applications when memory is constrained.
6. Test with default resource packs and without extra mods.

## Memory allocation

Do not allocate all system memory to Minecraft. Leave enough for the operating system, launcher, background applications, and integrated graphics. Increasing allocation beyond what the game needs does not automatically improve performance.

## Measure, don't guess

Compare the same scene under the same conditions. A change that raises peak FPS but worsens frame-time spikes may not feel better. For a repeatable method, read [Performance Features](../features/performance.md).

## Startup time

First launches may take longer because the launcher downloads files and the game initializes caches. Compare repeated launches separately from first-run downloads, and do not delete caches as a routine optimization unless troubleshooting guidance requires it.
