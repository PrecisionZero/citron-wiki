# Compatibility

Compatibility depends on the exact Citron build, Minecraft version, Fabric Loader version, mod versions, and any extra mods or resource packs installed.

## Supported baseline

Use the Minecraft version and loader specified by the release you downloaded. The development configuration documented here has targeted Minecraft 1.21.11 with Fabric; check the current release notes before relying on that as the latest supported version.

## Extra mods

Citron is tested as a particular combination of mods. Adding or updating individual mods can introduce dependency mismatches, duplicate features, conflicting mixins, keybind conflicts, or rendering issues.

For a clean test:

1. Duplicate the instance or back it up.
2. Test the unmodified pack.
3. Add one extra mod.
4. Launch and test the relevant feature.
5. Keep a record of the mod version if the issue appears.

## Shaders and resource packs

Visual additions can change performance or override assets. Test without them before reporting a core pack issue.

## Report compatibility problems

Include the Citron build, Minecraft version, loader version, launcher, added mods, shader/resource-pack names, and the latest relevant log. See [Reporting an Issue](../support/issue-reporting.md).
