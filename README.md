# @matzkoh/renovate-config

This is a shareable configuration for [Renovate](https://renovatebot.com/), a tool that helps automate dependency updates.

## Usage

To use this configuration, add the following to your `renovate.json` file:

```json
{
  "extends": ["github>matzkoh/renovate-config"]
}
```

## Concepts

- This configuration prefers using version pins for npm packages.
- It automatically merges patch-level updates for all dependencies.
- It automatically merges minor-level updates for dev dependencies.
- It rebases outdated pull requests.
- It maintains lock files on a weekly basis.

The config presets are stored in [default.json](default.json).
