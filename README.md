# Gamble Rigging (Fabric, Minecraft 1.21.11)

Press **I** to open the casino GUI, pick **LEFT** (Cookie) or **RIGHT** (Paper).
The side you pick always rolls the higher number. Press **I** again (or ESC) to close.

## Get the .jar

### Option 1: GitHub builds it for you (no local setup)
1. Create a new GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Open the repo's **Actions** tab, then the "Build mod jar" run, and download the `gamble-rigging-jar` artifact.
3. Unzip it. `gamble-rigging-1.0.0.jar` is the mod.

### Option 2: Build locally
1. Install JDK 21 and Gradle 9.2+.
2. In this folder run: `gradle build`
3. The mod is `build/libs/gamble-rigging-1.0.0.jar` (not the `-sources` jar).

## Install
Put the jar in `.minecraft/mods/` together with Fabric Loader and Fabric API for 1.21.11.
For multiplayer, install it on the server AND on every client that should use it.
