# RenovateBot Configurations

To use, add a `renovate.json` file to the root of your repo that extends this configuration:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>bymbly/renovate-config"]
}
```

Optionally, you can select a specific preset, such as:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>bymbly/renovate-config:libs"]
}
```

## Available Presets

- default (implicit) - pins dependencies
- libs - for libraries, uses the `widen` rangeStrategy
