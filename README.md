# Mapster-CoA

**Mapster-CoA v1.1.1** is a world-map customization addon for **Ascension Conquest of Azeroth / Conquest Reborn**, using the WoW 3.3.5a client.

> **[Download Here!](https://coa-research.unclebone.workers.dev/download/Mapster-CoA)**
**Current stable release: v1.1.1.**

This project packages Mapster and integrated Magnify-style zoom as **one addon**. A separate Magnify or Magnify-WotLK installation is not required.

## Features

- Mouse-wheel world-map zoom integrated into Mapster
- World-map customization and scaling
- Player coordinates and group map icons
- Fog-of-war and instance-map functionality
- Zoom options included in the Mapster addon

## Compatibility

Designed for Conquest Reborn (Interface 30300). Version 1.1.1 includes a source-level ElvUI-CoA compatibility adjustment: integrated zoom no longer overwrites the ElvUI backdrop positioning method or forcibly reanchors its world-map skin. Texture paths for player and party map icons were also corrected.

**Still requires in-game combination testing:** ElvUI-CoA, DragonUI, Questie-X, LootCollector, SilverDragon, Zygor-CoA, SexyMap-CoA, ConquestWorldMapImprovements, and other map overlays. Compatibility is a project goal, not a blanket certification.

## Installation

1. Download the [v1.1.1 release ZIP](https://github.com/uncle-bone/Mapster-CoA/releases/latest).
2. Place the included `Mapster` folder into `World of Warcraft/Interface/AddOns/`.
3. Remove or disable any separately installed Magnify/Magnify-WotLK addon to avoid duplicate zoom handlers.
4. Restart the game and configure Mapster through Interface Options.

**Folder structure:** `Interface/AddOns/Mapster/Mapster.toc`

## Version history

- **1.1.1** — ElvUI-CoA map-backdrop compatibility adjustment and integrated zoom texture-path corrections.
- **1.1.0** — Magnify zoom functionality integrated into Mapster.
- **1.0.0** — Conquest Reborn project version baseline.

## Maintainer

**Uncle Bone** — [uncle-bone](https://github.com/uncle-bone)

## Credits and licensing

Based on the original Mapster addon by Nevcairiel and Magnify functionality from its upstream authors. Original third-party authorship, notices, and applicable licensing restrictions remain in effect; project versioning and maintenance do not imply original authorship of upstream code. See included source metadata and notices.
