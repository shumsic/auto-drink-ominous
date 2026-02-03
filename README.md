# Auto Drink Ominous

A tiny Meteor Client addon that automatically drinks an Ominous Bottle when a raid ends,
so you can chain raids at a raid farm without manual input.

## Features

- Detects raid victory via server sound + bossbar.
- Finds an Ominous Bottle in your hotbar.
- Optionally pulls a bottle from inventory into the hotbar.
- Prioritization mode: Leftmost or Highest Level.
- Auto-disable: never, after time, or after number of consumptions.
- Restores your previous hotbar slot after drinking.

## Requirements

- Minecraft 1.21.11
- Fabric Loader
- Fabric API
- Meteor Client (matching 1.21.11 build)
- Java 21

## Building

This project assumes you have Gradle (8.14.3+ recommended) installed on your system.

```bash
# in the project root
gradle clean build
```

The built jar will be in:

```text
build/libs/AutoDrinkOminous-x.x.x.jar
```

## License

MIT. See `LICENSE` for details.
