# RRR Non-Player Characters

## HUMANS!
- Adds non-player humans to the game.

## CONFIGURE YOUR OWN HUMANS!
- Create new custom NPCs, using the same config system used by my mod [RRR Monsters](https://github.com/astradamus/RRRMonsters) to configure other, non-human mobs.
- Equip your NPC with any armor or weapon that players can equip, including those from other mods.
- Customize every aspect of your human, from name to faction, exact damage dealt by type (Poison Sword, Lightning Bow) to damage weakness/resistance, items dropped, fine tune AI settings, even change size (Skinny Humans? Elves! Stout Humans? Dwarves!) and add color tinting, and add color particle effects like body-flame and body-smoke (more FX options in future versions). And more!
- Designed to work with other mods that use prefabs, so you can produce custom NPCs for use in popular customization mods like Tykea's [Creature Level and Loot Control](https://www.nexusmods.com/valheim/mods/495) or ASharpPen's [Spawn That](https://www.nexusmods.com/valheim/mods/453) and [Custom Raids](https://www.nexusmods.com/valheim/mods/278).
- Automatically syncs custom NPCs with servers, so each server can seamlessly offer a unique experience.


## Notes


- **Note: Alone, this mod only adds the NPCs to the game, but will not cause them to appear in spawn tables or events.**

- **In order to actually encounter NPCs, you will need another mod. My own mods [RRR Better Raids](https://www.nexusmods.com/valheim/mods/705) and [RRR Spawn Variety](https://www.nexusmods.com/valheim/mods/685) are already fully configured to work with this mod without extra work.**

- You can also use any other mod that enables custom mob spawns or custom raids, provided you can configure them yourself.
    - I highly recommend ASharpPen's [Spawn That](https://www.nexusmods.com/valheim/mods/453) and [Custom Raids](https://www.nexusmods.com/valheim/mods/278).
    - Prefab IDs for the new NPCs included in this mod are listed below.
    - Prefab IDs for your custom NPCs will follow the format "RRRN_NewPrefabName".

- You can also use any other mod that enables custom mob spawns or custom raids, provided you can configure them yourself. Prefab IDs for the mobs included in this mod are listed below.

# OLD VERSION USERS!
#### Converting Old Format Custom NPCs to the new JSON format.
- Back up your old CFG style NPC configs. They won't be deleted, but you can't be too careful.
- Back up your saves before updating. **If you do this wrong, the worst thing that can happen is any existing custom NPCs in your world will despawn.** Still, use backups!
- Start the game and load into a **NEW WORLD**, open your `com.alexanderstrada.rrrnpcs.cfg` file. At the bottom, under `ConvertOldConfigStyle`, put the Full Prefab IDs of all NPC configs you want converted, separated by commas, following the same format the old config used to reference them. You can even copy-paste the old config line you were using there. For instance, `RRRN_Example1, RRRN_Example2, RRRN_Example3`.
- In Valheim, enter a **NEW WORLD**. Let the game load completely. Once you're in the world, check your config folder. You should see all your .CFG files as well as new .JSON versions of those NPCs with all old settings transferred to the new format. Double-check that the settings were correct (they should be!), then you're safe to remove the old CFG files and start your world/server normally. Any JSON files matching the name format in any folder within configs will be loaded, there is no longer a need to name each file.

#
## Setup

Extract the dll file to your `Valheim\BepInEx\plugins` folder. Config files must be in `Valheim\BepInEx\config` (subfolders are okay). Config files will also be generated automatically if missing.

## Help!

If you need further assistance, feel free to bug me (@neurodr0me) in the Valheim Modding Discord at https://discord.gg/MXqWrn532w

#### Added Prefab IDs
- (Note: T1-T6 refers to progression tiers, Meadows > Forest > Swamp > Mountains > Plains > Endgame)
```
RRR_Hostile_T1
RRR_Hostile_T2
RRR_Hostile_T3
RRR_Hostile_T4
RRR_Hostile_T5
RRR_Hostile_T6
```