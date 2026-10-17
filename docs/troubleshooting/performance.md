# Performance Problems

## Low average FPS

- Reduce render distance.
- Test with shaders disabled.
- Lower resource-pack resolution or visual settings.
- Check whether the GPU or CPU is near full utilization.
- Test without extra mods.

## Stuttering

Stutter may be caused by chunk generation, memory pressure, garbage collection, background processes, driver behavior, or a mod conflict. Average FPS alone may not show the problem.

Test the same scene repeatedly and change one variable at a time. Note whether the stutter occurs during movement, chunk loading, combat, or at regular intervals.

## Long startup

Separate the first launch from subsequent launches. First-run downloads and setup can make the initial start unusually slow. Compare several later launches with the same instance and environment.

## Integrated graphics

Integrated graphics share system memory with the CPU. Avoid assigning nearly all RAM to Minecraft, and test without shaders before making other changes.

## Still slow?

Include hardware, operating system, Minecraft and Citron versions, render/simulation distance, shader status, memory allocation, and what workload triggers the slowdown.
