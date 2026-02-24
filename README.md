# LootConomy-spigot

## Runtime requirements

- Install `EconomyBridge` on the server before starting LootConomy.
- Install `nightcore` on the server before starting LootConomy.

LootConomy declares both plugins as required dependencies in `plugin.yml`, so Paper will refuse to load LootConomy until they are present.

## Build output

The build is configured to produce only the main plugin jar (`LootConomy-<version>.jar`).
A separate `-sources.jar` is intentionally disabled to avoid Paper's modern plugin loader detecting two jars with the same plugin name in `.paper-remapped`.
