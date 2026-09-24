# Create: Relicworks

**CurseForge:** [create-relicworks](https://www.curseforge.com/minecraft/mc-mods/create-relicworks)

Create recycle recipes for Relics 0.10 items. Optional Artifacts junk crushing.

Standalone NeoForge **1.21.1** addon. Works in any pack with **Create 6** and **[Relics](https://www.curseforge.com/minecraft/mc-mods/relics-mod)**. **[Artifacts](https://www.curseforge.com/minecraft/mc-mods/artifacts)** is optional.

## What it adds (recipes only — no new blocks)

| Recipe | Purpose |
|---|---|
| Crushing / milling each Relics 0.10 relic | Create XP nuggets, gold, Relic XP bottles |
| Heated mixer: 4 XP nuggets + gold nugget + bottle | Relic XP bottle |
| Crushing (if Artifacts is loaded) | Recycle hats / whoopee cushion / snorkel / flippers / onion ring |

Relics 0.10 does **not** register separate `*_broken` items. Broken is a model on the same ID, so Create JSON cannot tell broken from intact. Mill only relics you want recycled.

Does **not** mill powerful Artifacts (hearts, pendants, totems).

## Install

Drop the jar into your `mods/` folder alongside **Create** and **Relics**.

## Changelog (1.0.1)

Relics 0.10 registered item IDs only. Drop unregistered Relics 0.9 `*_broken` recipes.
