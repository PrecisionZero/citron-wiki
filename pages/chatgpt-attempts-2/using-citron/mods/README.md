# Mods

Citron is tested as a curated set of mods and configurations. You can personalise it, but extra mods may cause conflicts, duplicate features, or change performance.

{% tabs %}
{% tab title="Add a mod" %}
1. Open your Citron instance in your launcher.
2. Use the launcher's content browser or open the instance folder, depending on how the mod is distributed.
3. Check that the mod supports the same Minecraft version and Fabric loader as your Citron build.
4. Read the mod's dependencies and install instructions.
5. Add one mod, launch the game, and test it before adding another.
{% endtab %}

{% tab title="Remove a mod" %}
1. Back up your instance first.
2. If it is a mod you added yourself, remove that mod and test again.
3. Before removing a bundled mod, check whether it provides a feature or dependency that other mods need.
4. Launch Citron after each change so you can tell which change caused a problem.
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Do not remove libraries or dependencies just because their purpose is unclear. Removing a bundled mod can break another mod or stop Citron from launching.
{% endhint %}

If you want to return to Citron's tested setup, a fresh instance is often easier than trying to reconstruct which files were changed.
