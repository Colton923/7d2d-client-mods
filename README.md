# 7 Days to Die — Client Mods

Auto-generated client mod package for our modded server.

## Installation

1. Clone this repo (or download as ZIP)
2. Copy all mod folders into your 7D2D Mods directory:
   ```
   <Steam>/steamapps/common/7 Days To Die/Mods/
   ```
3. Your Mods folder should look like:
   ```
   Mods/
   ├── 020_WeaponOverhaul/
   ├── 025_TraitSystem/
   ├── 060_ProgressionOverhaul/
   └── ... (other mods)
   ```

## Updating

```bash
git pull
```

Then restart your game. The server and client mods must match.

## What's Included

Only the files your game client needs:
- **ModInfo.xml** — mod metadata
- **Config/*.xml** — item/progression/loot overrides
- **Config/Localization.txt** — UI text for custom perks and traits
- ***.dll** — Harmony patches for UI and gameplay

Server-only files (source code, scripts, save data) are NOT included.

---

*This repo is auto-published by `deploy-client-mods.sh`. Do not edit directly.*
