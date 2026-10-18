# Resource Pack Troubleshooting

Resource packs can behave differently depending on Minecraft version, pack contents, and other mods that affect rendering. If a pack looks wrong, try these checks first.

## The pack won't load

* Check that the resource pack supports your Minecraft version.
* Make sure the downloaded file is the resource pack itself, not a website or installer archive.
* Open **Options → Resource Packs** and confirm the pack is enabled.
* Check Minecraft's messages for an incompatibility or broken-file warning.

## Textures or models look wrong

1. Change the pack's position in the resource-pack list to test whether pack priority is the cause.
2. Disable other resource packs and test the problem pack by itself.
3. Check whether the pack requires OptiFine-specific features or another mod that Citron does not include.
4. Confirm that the pack supports the rendering mods included in your Citron build.

## The problem started after an update

Check the version notes and test with a clean resource-pack list. If the pack works without other additions, add those additions back one at a time.

If the issue remains, report the resource-pack name and version, your Citron build, and a screenshot of the problem.
