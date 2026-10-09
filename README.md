# One Piece Ultimate Mod — starter project

**Target:** Minecraft Java 26.3, Fabric, Android launcher such as MJLauncher  
**Status:** starter source project only; not a finished or tested `.jar`.

## Included now
- Fabric mod project structure and entrypoint.
- Gradle build configuration targeting Minecraft 26.3 / Fabric.
- A starter JSON catalogue of example Devil Fruits and planned systems.

## Important
The catalogue is a planning file: it does **not** register fruit items in-game yet. This project does not yet contain finished models, textures, powers, transformations, bosses, islands, or NPCs. Those need to be implemented and tested incrementally.

## Build requirements
- JDK 25
- Gradle 9.6 or compatible with the selected Fabric Loom version
- Internet access to download Minecraft/Fabric build dependencies

From this folder, run:

```sh
gradle build
```

If the build succeeds, the JAR should be in `build/libs/`. This environment did not compile or test the project, so do not assume the JAR will work until it has been built and tested with your exact MJLauncher instance.

## Next development milestones
1. Verify the build against Fabric's current 26.3 template.
2. Register a first test Devil Fruit item.
3. Add a simple ability with server-side validation and cooldown.
4. Add the Nika transformation states and Gear 2 / 3 / 4 variants / Gear 5.
5. Add the three Haki systems.
6. Add additional fruit families, items, bosses, loot, and NPCs.
7. Test on a backup world in MJLauncher.

## Note about names and assets
This is a fan-made project plan, not an official One Piece or Minecraft product. Use original or appropriately licensed textures, sounds, and models.
