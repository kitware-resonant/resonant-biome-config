# resonant-biome-config
[![npm (scoped)](https://img.shields.io/npm/v/@resonant/biome-config)](https://www.npmjs.com/package/@resonant/biome-config)

A shared Biome linter configuration for Resonant projects.

## Installation
```bash
npm install --save-dev @biomejs/biome @resonant/biome-config
```

In `biome.json`:
```json
{
  "$schema": "https://biomejs.dev/schemas/2.3.10/schema.json",
  "extends": ["@resonant/biome-config"]
}
```
