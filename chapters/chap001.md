---
name: Watershed
game_date: 4656-03-29
pcs: "[Repent](../pcs/Repent.md), [Conan](../pcs/Conan.md), [Elk](../pcs/Elk.md), [Robert](../pcs/Robert.md), [Davi](../pcs/Davi.md)"
levels: 

meta:
  category: chapter
  campaign: Nibiru
  sector: "Fomalhaut Settlement Zone"
  system: "Fomalhaut"
  world: "Nibiru Station"
  realm: "Outback Domains"
  region: "Ascendant V trail"
  location: "Outside Wellshed"
tags: 
---

> [!todo]- Planning checklist & tracker
> ![_tracker](../_tracker.md)

> [!abstract] Motivations & Themes
> 
> **Present characters**
> - Repent: 
> - Conan:
> - Elk:
> - Robert:
> - Davi:
> 
> **Absent characters**
> - Repent: 
> 
> **Tarot cards theme**:
> - Vortex
> - Rebelion

> [!quote] Factions 
> ```dataview
> table without ID link(file.link, name) AS "Faction", h + e + r as "Challenge", h as "H", e as "E", r as "R"
> from "nibiru/factions"
> WHERE contains(meta.category, "faction")=true
> sort id asc
> ```

> [!warning] Intro
> - 

> [!danger] Strong start

1. **Ambient Description**:
	1. The **ceiling** is dotted with **flickering** lights and occasional sparks from exposed wiring.
	2. The air is filled with a low, constant **hum** of **machinery** and distant echoes of moving transport vessels.
2. **Meet Vaelen Sorra**: The Vagabonds encounter [VaelenSorra](../npcs/VaelenSorra.md), the exiled scholar, outside the ruined construction.
	4. He provides cryptic information about the area and hints at valuable knowledge hidden deeper in the tunnels.
	5. Vaelen describes the labyrinthine tunnels as a vortex of forgotten paths and lost souls, emphasizing the disorienting and cyclical nature of their journey.
3. **Labyrinthine Network**: The environment should feature a maze-like network of **service tunnels and air ducts**, scattered with derelict **industrial** buildings and piles of **scrap machinery**. `vortex`

![](https://i.imgur.com/PxIZfJk.png)

> [!example] Sets

**Industrial Wastegrounds** `rebelion`
- Meet [RheaArgyros](../npcs/RheaArgyros.md), who initially mistrusts the group but can be convinced to help. Friend of Vaelen
- Rhea shares stories of her involvement in small rebellions against the ruling factions of Tharsus, showcasing her defiance and resourcefulness.
	- They are scouting for a caravan of Enesu in an important mission.
- You are **extremely exhausted**
	- Sleep underwater.

- Wake up with [RheaArgyros](../npcs/RheaArgyros.md)
	- **Slept well**? Look at questions for players
	- To Caravan dinner scene.

![](https://i.imgur.com/qyPKXXx.png)


- Dinner Set
	- Meet [NabuaAmarud](../npcs/NabuaAmarud.md)

- Wire thikett
	- Work with [Tauthe](../npcs/Tauthe.md)

> [!bug] Random encounters

| 2d6 | Encounter                                                                                                                                    |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 2   | **Feral Tech-Scavengers** (humans): A group of mutated humanoids scavenging for valuable scrap.                                              |
| 3   | **Rogue Maintenance Drone** (systems malfunction): A malfunctioning and erratic drone performing destructive tasks.                          |
| 4   | **Bioluminescent Fungus Patch** (environment effects): Area filled with glowing fungi and hallucinogenic spores.                             |
| 5   | **Crazed Hermit** (personal panic): A lone survivor, driven mad by isolation, who claims to have vital information about a hidden treasure.  |
| 6   | **Collapsed Tunnel** (environment effects): A recently collapsed section blocking the path, home to mutated insects.                         |
| 7   | **Echoing Whispers** (wondrous event): Eerie, disembodied whispers filling the tunnels, remnants of a failed AI experiment.                  |
| 8   | **Lost Caravan** (humans): A small group of survivors from a lost caravan seeking help.                                                      |
| 9   | **Aggressive Wildlife** (Nibiru creatures): Bioelectric foxes defending their territory.                                                     |
| 10  | **Resource Cache** (wondrous event): A hidden cache of valuable supplies and ancient artifacts.                                              |
| 11  | **Fallen Ascendant** (systems malfunction): A crashed vessel with salvageable parts and potential dangers.                                   |
| 12  | **Guardian AI** (wondrous event): An ancient, malfunctioning AI that mistakes the Vagabonds for intruders and activates defensive protocols. |

> [!info] Information pool
> ![infoPool](../_infoPool.md)

> [!tip] Interaction table 
> 
> ```dataview
> TABLE without ID link(file.link, name) as Entity, file.folder as Type, file.outlinks as "Further interactions"
> FROM outgoing([[]]) 
> SORT file.folder ASC
> WHERE contains(file.folder, "nibiru/")
> ```
