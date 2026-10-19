---
description: Fix resource packs that fail to load or render incorrectly in Citron.
---

# Resource Pack Troubleshooting

Resource packs don't all work the same way. A pack may be outdated, depend on features Citron doesn't include, or conflict with another pack you've enabled.

## The pack won't load

1. Check that the pack supports your Minecraft version.
2. Make sure you downloaded the actual resource-pack file, not an installer or a web page.
3. Open **Options → Resource Packs** and confirm the pack is enabled.
4. If Minecraft shows a warning about an incompatible pack, read it before choosing to continue.

## Textures or models look wrong

1. Disable your other resource packs and test the problem pack by itself.
2. Change the pack's position in the list to check whether another pack is overriding its textures.
3. Check whether it needs OptiFine-specific features or another mod that isn't included in your Citron build.
4. If the problem concerns connected textures, make sure the pack supports the rendering mods in your version of Citron.

## It broke after an update

Check the Minecraft version the pack supports, then test it with other resource packs disabled. If you recently added a mod or shader, disable that too and test again.

If the issue remains, include the resource-pack name and version, your Citron build ID, and a screenshot when you [report the issue](../../help/report-an-issue.md).
