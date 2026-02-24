# OrbisLoot

## Runtime requirements

- Install `EconomyBridge` on the server before starting OrbisLoot.
- Install `nightcore` on the server before starting OrbisLoot.

OrbisLoot declares both plugins as required dependencies in `plugin.yml`, so Paper will refuse to load OrbisLoot until they are present.

## Build output

The build is configured to produce only the main plugin jar (`OrbisLoot-<version>.jar`).
A separate `-sources.jar` is intentionally disabled to avoid Paper's modern plugin loader detecting two jars with the same plugin name in `.paper-remapped`.
