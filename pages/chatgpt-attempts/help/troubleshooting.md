# Troubleshooting

Try these checks before reporting a problem. The cause can depend on your Citron build, launcher, Minecraft version, and any changes you have made to the instance.

## The game will not launch

1. Confirm that you installed the correct Citron file for the Minecraft version you want to play.
2. Restart your launcher and try again.
3. If you added mods, shaders, or resource packs, test a clean Citron instance without them.
4. Check the launcher's error message and the game log for the first relevant error.
5. Confirm that your system meets Minecraft's requirements and has enough memory available.

## The game crashes after adding a mod

Remove or disable the most recently added mod and test again. Check that it supports the same Minecraft version and Fabric loader as Citron and that its dependencies are installed.

## A feature or setting is missing

Check the documentation for your exact Citron version. Features and configuration options can change between builds. If the option should be present, test with the original Citron configuration and check [Changed Options and Menu](../features/changed-options-and-menu.md).

## Resource packs or shaders look wrong

Disable the resource pack or shader and test again. Check version compatibility and resource-pack priority. See [Resource Pack Troubleshooting](../technical-guide/resource-packs-and-shaders/resource-pack-troubleshooting.md).

## Performance is poor

Test without shaders or extra mods, lower demanding video settings, and close unnecessary background applications. Compare the same world and settings before drawing conclusions. See [Improving Performance](../technical-guide/improving-performance.md).

## After an update

Check the version notes and confirm that your settings and extra mods still support the new Minecraft version. If needed, install a clean instance to see whether the problem is caused by your personal changes.

If the issue continues, follow [Report an Issue](report-an-issue.md).
