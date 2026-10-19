---
description: Check a build's Minecraft version and loader before installing it.
---

# Version Support

Citron builds target a specific Minecraft version and mod loader. Check these details on the exact file you want to download; don't assume a newer Citron build automatically supports a newer Minecraft release.

The repository's current development notes identify `1.0.0-dev.8+mc1.21.11.fabric` as a build for **Minecraft 1.21.11 with Fabric**. This is a development build, so future versions may target something different.

## Before installing

* Check the Minecraft version listed for the build.
* Confirm that it uses Fabric where required.
* Make sure any extra mods match the same Minecraft version and loader.
* For multiplayer, check that the server supports the Minecraft version you're using.

## Understanding the build ID

`1.0.0-dev.8+mc1.21.11.fabric` is made up of these parts:

| Part        | Meaning                  |
| ----------- | ------------------------ |
| `1.0.0`     | Intended release version |
| `dev.8`     | Development build number |
| `mc1.21.11` | Target Minecraft version |
| `fabric`    | Mod loader               |

The development number advances with each build, even when the change is small. The original identifiers are kept in the development record for traceability.

See [Version History](version-history.md) or the full [Development Stages log](https://github.com/PrecisionZero/citron/blob/main/Developer/Development_stage.md) for details.
