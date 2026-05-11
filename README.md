# BannerHub Game Configs
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?logo=discord&logoColor=white)](https://discord.gg/n8S4G2WZQ4)


Community-shared game configurations for [BannerHub](https://github.com/The412Banner/BannerHub).

**🌐 Browse online:** [the412banner.github.io/bannerhub-game-configs](https://the412banner.github.io/bannerhub-game-configs/) — search by game, filter by manufacturer/device, compare configs side by side, download JSON files.

## What's stored here

Each folder under `configs/` is a game name. Inside each folder are JSON config files named:

```
<Manufacturer>-<Model>-<Timestamp>.json
```

Example:
```
configs/
  Cyberpunk_2077/
    samsung-SM-S911B-1743710400.json
    OnePlus-CPH2449-1743698200.json
  Elden_Ring/
    samsung-SM-S911B-1743698000.json
```

## File format

Each config contains the game's settings and the custom components it requires:

```json
{
  "settings": {
    "winlator_env_dxwrapper": "DXVK-2.3.1",
    "winlator_env_box64version": "Box64-0.3.2",
    ...
  },
  "components": [
    { "name": "DXVK-2.3.1", "url": "https://...", "type": "DXVK" },
    { "name": "Box64-0.3.2", "url": "https://...", "type": "Box64" }
  ]
}
```

## Usage

Configs are uploaded and downloaded directly through the BannerHub app via the
**Export Config** and **Import Config** options in the game settings menu.

Do not submit configs manually — they are managed by the app.


## Community

Join our Discord: https://discord.gg/n8S4G2WZQ4
