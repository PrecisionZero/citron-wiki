# Development and Release Cycle

Citron follows Adrenaline's performance foundation while maintaining its own selection of features, configurations, and interface changes.

When Adrenaline supports a new Minecraft version or publishes a patch, Citron may follow after the relevant changes have been reviewed and tested. Timing is not guaranteed: dependencies, compatibility issues, or Citron-specific work can delay a build.

## Development build IDs

Citron's development identifiers use the format `1.0.0-dev.N+mcVERSION.fabric`.

* `1.0.0` is the intended release version.
* `dev.N` identifies the development build and advances with each new development build.
* `mcVERSION` records the Minecraft version.
* `fabric` records the loader.

Original build IDs are retained in the development records for traceability. Development builds can change more frequently than stable releases, so do not assume that a development build is equivalent to a final release.

For recorded changes, see the [Citron development history](https://github.com/PrecisionZero/citron/blob/main/Developer/Development_stage.md) and the wiki's [Citron Versions](../../getting-started/versions/index.md) section.
