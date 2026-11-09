# Controlify Cobblemon Flight

A client-only Fabric mod for Minecraft 1.21.1 that makes ridden Cobblemon Pokémon flight use the player's normal movement input. It does not load or install gameplay code on a dedicated server. Controlify feeds controller bindings into that input, so the flight controls work with a controller in the same way as keyboard and mouse movement.

The mod detects a ridden Cobblemon Pokémon in its flying state, reads forward, strafe, jump, and sneak input from the controlling player, and applies it to the Pokémon. The left stick controls horizontal flight. The jump and sneak bindings move up and down.

## Requirements

- Minecraft 1.21.1
- Fabric Loader 0.16.5 or newer
- Fabric API
- Cobblemon 1.6.0 or newer for Minecraft 1.21.1
- Controlify 2.0.0 or newer for Minecraft 1.21.1

## Installation

1. Install Fabric Loader for Minecraft 1.21.1.
2. Install Fabric API, Cobblemon, and Controlify in the same instance.
3. Build this project and copy `build/libs/controlify-cobblemon-flight-1.0.0.jar` into the instance's `mods` folder.
4. Start Minecraft and ride a flying Cobblemon Pokémon.

## Build

Use Java 21 and run:

```bash
./gradlew build
```

The finished mod jar appears under `build/libs`.
