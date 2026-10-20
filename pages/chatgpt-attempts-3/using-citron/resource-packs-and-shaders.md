---
description: Install visual packs and check compatibility with your Citron build.
icon: image
---

# Resource Packs and Shaders

Resource packs change textures, sounds, and other parts of Minecraft's presentation. Shaders change rendering and can have a bigger impact on performance.

## Resource packs

{% stepper %}
{% step %}
## Download a compatible pack

Check the supported Minecraft version and download the pack from a source you trust.
{% endstep %}

{% step %}
## Open the correct folder

In Minecraft, open **Options → Resource Packs** and use **Open Pack Folder**.
{% endstep %}

{% step %}
## Add and enable it

Place the downloaded resource-pack file in that folder, return to Minecraft, and enable it. If packs change the same assets, their order determines which changes take priority.
{% endstep %}
{% endstepper %}

## Shaders

Before installing a shader, confirm that the Citron build has a compatible shader loader. The development record includes Iris Shaders, but the exact file you use is what matters.

1. Open **Options → Video Settings** and check whether a Shader Packs screen is available.
2. Download a shader that supports your Minecraft version and graphics setup.
3. Use the Shader Packs screen's folder option if available, add the shader ZIP, then select and apply it.

## If something looks wrong

Disable other packs and shaders and test the new one by itself. Check whether it needs OptiFine-specific features or another mod that Citron doesn't include. If performance drops, disable the shader or reduce its settings.

## Related guides

* [Performance Tips](performance-tips.md)
* [Troubleshooting](../help/troubleshooting.md)
