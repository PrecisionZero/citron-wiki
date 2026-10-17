# Launch Failures and Crashes

## The game closes before the title screen

1. Confirm the selected Minecraft version and Fabric instance.
2. Let the launcher finish downloading dependencies.
3. Check whether the launcher reports a Java runtime error.
4. Test the original Citron instance without extra mods.
5. Open the latest log and crash report, if one exists.

## A missing dependency is reported

Use the pack as distributed and avoid manually updating individual mods. A mod may require a specific library or version. Reinstalling or importing a clean copy of the correct release can restore missing files.

## The game crashes after adding a mod

Remove the newly added mod and test again. Check its supported Minecraft version, loader, required dependencies, and whether it duplicates an existing feature.

## The game crashes in a world

Test a new temporary world. If only one world fails, back up that world before further testing. Do not repeatedly open a valuable world while changing Minecraft versions.

## What to include in a report

Share the latest crash report or relevant log excerpt, the exact build, launcher, Java version if known, and a short description of what happened immediately before the crash. See [Reading Logs](logs.md).
