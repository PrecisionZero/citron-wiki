# Performance Tips

Citron already includes performance optimisations, but your settings and hardware still affect how Minecraft runs. Try one change at a time so you can tell what actually helped.

## Start here

* **Render distance:** Lower it if terrain takes too long to load or draw.
* **Simulation distance:** Lower it if your CPU struggles with entities and world activity.
* **Shaders:** Disable them while checking baseline performance.
* **Extra mods:** Test without additions before assuming Citron itself is the cause.
* **Background apps:** Close programs you do not need while playing.
* **Memory:** More RAM is not automatically better. Leave enough for Windows and other applications.

## Compare fairly

Use the same world, Minecraft version, render distance, and video settings. Let the world load before recording FPS, and repeat the test. A single number is not enough to prove that one build is faster than another.

{% hint style="info" %}
If Citron performed well before an update, test the new build in a clean instance with the same settings before changing many options. This makes it easier to isolate a regression.
{% endhint %}

If performance is still poor, include your hardware, Citron build ID, video settings, and whether shaders or extra mods are enabled when reporting the problem.
