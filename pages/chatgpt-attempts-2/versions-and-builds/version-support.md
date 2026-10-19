---
description: >-
  Learn how Citron's development build IDs work and how to choose a compatible
  version.
---

# Version Support

The repository's development information identifies `1.0.0-dev.8+mc1.21.11.fabric` as a development build for Minecraft `1.21.11` using Fabric. Check the official Citron project listing before downloading, as published files can change.

## Choosing a version

* Check the Minecraft version and loader shown for the exact Citron file you want.
* Install a build that matches the Minecraft version you intend to play.
* Don't assume that a newer Minecraft release is supported until Citron has a compatible build.
* If you're testing a different Minecraft version or development build, make a separate instance when possible.

## Reading the build ID

Citron uses identifiers like `1.0.0-dev.N+mcVERSION.fabric`.

| Part        | Meaning                                            |
| ----------- | -------------------------------------------------- |
| `1.0.0`     | Intended release version                           |
| `dev.N`     | Development build number; advances with each build |
| `mcVERSION` | Minecraft version                                  |
| `fabric`    | Mod loader                                         |

The `dev.N` number advances with each development build, regardless of how big the changes are. Original build IDs are kept in the development records for traceability.

See [Version History](version-history.md) or [Citron's development history on GitHub](https://github.com/PrecisionZero/citron/blob/main/Developer/Development_stage.md) for recorded changes.
