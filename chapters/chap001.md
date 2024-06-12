---
name: Watershed
game_date: 4225-03-29
pcs: "[Repent](../pcs/Repent.md), [Conan](../pcs/Conan.md), [Elk](../pcs/Elk.md), [Robert](../pcs/Robert.md), [Davi](../pcs/Davi.md)"
levels: 

meta:
  category: chapter
  campaign: Nibiru
  sector: "Fomalhaut Settlement Zone"
  system: "_Fomalhaut_"
  world: "Nibiru Station"
  realm: "Outback Domains"
  region: "Ascendant V trail"
  location: "Outside Wellshed"
tags: 
---

> [!todo]- Planning checklist & tracker
> - [ ] Abridge previous chapter and distribute XP
> - [x] Commit next chapter draft and check metadata
> - [ ] Clean up previous chapter files, update tags and name, make final commit
> - [ ] Update (battle)maps, if applicable
> - [ ] Update oracle
> - [ ] Draw two tarot cards to inform prep
> - [ ] Define at least one consequence in the world of the actions of the PCs on the previous session, record it in notion file and change one faction's attribute (+/-)
> - [ ] Think about characters, write motivations & hooks
> - [ ] Evaluate new game date
> - [ ] Review Abridged
> - [ ] Evaluate Faction turn
> - [ ] Review and organise Notions
> - [ ] Detail strong start
> - [ ] Outline situations:
> 	- [ ] Draft locations 
> 	- [ ] Draft NPCs
> 	- [ ] Prepare random encounters table
> 	- [ ] Prepare Owlbear, if applicable
> - [ ] Review and order/highlight information pool.
> - [ ] Update random encounter tables
> - [ ] Print information pool (applicable parts)
> 
>> [!done]- Tracker 
>> ```dataview
>> table without ID link(file.link, name) AS "Chapter", game_date AS "Date", pcs as "PCs", levels as "Rank", meta.sector as "Sector", meta.system as "System", meta.world as "World", meta.location as "Location"
>> from "nibiru/chapters"
>> sort file.name asc
>> ```

> [!abstract] Motivations & Themes
> **Characters**
> - Repent: 
> - Conan:
> - Elk:
> - Robert:
> - Davi:
> 
> **Tarot cards theme**:
> - ...
> - ...

> [!quote] Factions 
> ```dataview
> table without ID link(file.link, name) AS "Faction", stats[0].cunning + stats[1].force + stats[2].wealth as "Level", meta.die as "Die", stats[0].cunning as "C", stats[1].force as "F", stats[2].wealth as "W"
> from "nibiru/factions"
> WHERE contains(meta.category, "faction")=true
> sort id asc
> ```
> 
> **xx round**
> - 
> 

> [!warning] Intro
> - 


> [!danger] Strong start

- Meet [VaelenSorra](../npcs/VaelenSorra.md) outside the ruined construction.
- Labyrinthine network of service tunnels and air ducts, interspersed with derelict industrial buildings. 
- Cracked tiles and scattered debris from long-abandoned structures, piles of scrap machinery.
- On the outside:
	- Vast expanse of interlocking metal and synthetic materials, dimly illuminated by the distant glow of Ascendant V.
	- This massive transport vessel occasionally casts its shadow over the area, a reminder of the technological marvels that roam the vast corridors of Nibiru.
	- The ceiling is dotted with flickering lights and the occasional spark from exposed wiring, creating an eerie, perpetually twilight ambiance.
	- The air is filled with a low, constant hum of machinery and the distant echoes of moving transport vessels. 

![](https://i.imgur.com/PxIZfJk.png)



> [!example] Situations 

- Meet [RheaArgyros](../npcs/RheaArgyros.md)
	- During caravan travel.
	- Slept well? Look at questions for players
	- Caravan dinner scene.

- Meet [NabuaAmarud](../npcs/NabuaAmarud.md)

- Wire thikett
	- Work with [Tauthe](../npcs/Tauthe.md)



> [!bug] Random encounters

1. **Feral Tech-Scavengers**
   - **Description:** A group of mutated humanoids, once humans, now twisted by the harsh environment and exposure to toxic substances. They are scavenging for valuable scrap and technology.
   - **Encounter:** The scavengers notice the party and, driven by desperation, attempt to ambush them for their supplies. Combat may ensue, or the party can negotiate to avoid conflict.
   - **Loot:** Various pieces of broken tech, makeshift weapons, and a rare component needed for a future quest.

2. **Rogue Maintenance Drone**
   - **Description:** An old maintenance drone, malfunctioning and erratic, roams the tunnels, performing random and often destructive tasks.
   - **Encounter:** The drone mistakes the party for debris and tries to dismantle them. The party can attempt to disable it or reprogram it to gain a useful ally.
   - **Loot:** Drone parts, a power core, and a map fragment stored in its memory.

3. **Bioluminescent Fungus Patch**
   - **Description:** A dense cluster of glowing fungi that emit a faint, eerie light. The area is filled with spores that affect the mind and body.
   - **Encounter:** As the party passes through, they must make checks to avoid the hallucinogenic effects of the spores. They might see visions or suffer temporary impairments.
   - **Loot:** Samples of the fungi, which can be used for crafting or sold to certain NPCs.

4. **Crazed Hermit**
   - **Description:** A lone survivor, driven mad by isolation and the relentless environment. He claims to have vital information about a hidden treasure in the ruins.
   - **Encounter:** The hermit is initially hostile but can be calmed with careful negotiation. He may offer cryptic clues or misleading information, depending on how the party treats him.
   - **Loot:** A handmade map, a stash of old-world relics, and a piece of lore about the region.

5. **Collapsed Tunnel**
   - **Description:** A recently collapsed section of the tunnel, blocking the path forward. The rubble is unstable and dangerous to navigate.
   - **Encounter:** As the party attempts to clear the debris or find another way around, they disturb a nest of giant, mutated insects that attack to defend their home.
   - **Loot:** Among the rubble, they find a hidden cache containing valuable supplies and an ancient artifact.

6. **Echoing Whispers**
   - **Description:** The tunnels are filled with eerie, disembodied whispers that seem to come from nowhere and everywhere at once.
   - **Encounter:** The whispers are the remnants of a failed AI experiment, now haunting the corridors. It seeks to communicate but is fragmented and dangerous. The party must decipher its messages while avoiding traps set by the AI to protect itself.
   - **Loot:** Access codes to a nearby secured facility, a data chip with encrypted information, and advanced medical supplies.

> [!info]- Information pool
> ![_hostileInformationPool](../_hostileInformationPool.md)

> [!tip] Interaction table 
> 
> ```dataview
> TABLE without ID link(file.link, name) as Entity, file.folder as Type, file.outlinks as "Further interactions"
> FROM outgoing([[]]) 
> SORT file.folder ASC
> WHERE contains(file.folder, "nibiru/")
> ```
