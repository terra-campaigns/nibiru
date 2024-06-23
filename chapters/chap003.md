---
name: 
game_date: v4 c500 d85
pcs: 
levels: 

meta:
  category: chapter
  campaign: Nibiru
  sector: "Fomalhaut Settlement Zone"
  system: "Fomalhaut"
  world: "Nibiru Station"
  realm: "Outback Domains"
  region: "Ascendant V trail"
  location: "Arwia's Realm"
tags: 
---

> [!todo]- Planning checklist & tracker
> ![_tracker](../_tracker.md)

> [!abstract] Motivations & Themes
> 
> - [Repent](../pcs/Repent.md):
> - [Conan](../pcs/Conan.md) (Bright Town):
> - [Elk](../pcs/Elk.md):
> - [Robert](../pcs/Robert.md) (Wild): Recuperar suas memórias.
> - [Zumathi](../pcs/Zumathi.md):
> - [Davi](../pcs/Davi.md): 
> 
> **Tarot cards theme**:
> -  
> - 

> [!quote] Factions 
> ```dataview
> table without ID link(file.link, name) AS "Faction", h + e + r as "Challenge", h as "H", e as "E", r as "R"
> from "nibiru/factions"
> WHERE contains(meta.category, "faction")=true
> sort id asc
> ```

> [!warning] Intro
> - Confirmar saldo de MP e memórias.

> [!example] Sets

Conan e o ritual.

Rhea sumida.


Cenas da aventura? Tarot cards.

> [!info] Information pool
> ![infoPool](../_infoPool.md)

> [!bug] Random encounters

| 1d6 | Encounter                                                                                                                                    |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Feral Tech-Scavengers** (humans): A group of mutated humanoids scavenging for valuable scrap.                                              |
| 2   | **Rogue Maintenance Drone** (systems malfunction): A malfunctioning and erratic drone performing destructive tasks.                          |
| 3   | **Crazed Hermit** (personal panic): A lone survivor, driven mad by isolation, who claims to have vital information about a hidden treasure.  |
| 4   | **Collapsed Tunnel** (environment effects): A recently collapsed section blocking the path, home to mutated insects.                         |
| 5   | **Echoing Whispers** (wondrous event): Eerie, disembodied whispers filling the tunnels, remnants of a failed AI experiment.                  |
| 6   | **Lost Caravan** (humans): A small group of survivors from a lost caravan seeking help.                                                      |
|     | **Aggressive Wildlife** (Nibiru creatures): Bioelectric foxes defending their territory.                                                     |
|     | **Resource Cache** (wondrous event): A hidden cache of valuable supplies and ancient artifacts.                                              |
|     | **Fallen Ascendant** (systems malfunction): A crashed vessel with salvageable parts and potential dangers.                                   |
|     | **Guardian AI** (wondrous event): An ancient, malfunctioning AI that mistakes the Vagabonds for intruders and activates defensive protocols. |

> [!tip] Interaction table 
> 
> ```dataview
> TABLE without ID link(file.link, name) as Entity, file.folder as Type, file.outlinks as "Further interactions"
> FROM outgoing([[]]) 
> SORT file.folder ASC
> WHERE contains(file.folder, "nibiru/")
> ```
