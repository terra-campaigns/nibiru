---
name: Árvore da Família
game_date: v4 c500 d80
pcs: Conan, Robert, Zumathi
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
> - [Conan](../pcs/Conan.md):
> - [Elk](../pcs/Elk.md):
> - [Robert](../pcs/Robert.md) (Wild): Recuperar suas memórias.
> - [Zumathi](../pcs/Zumathi.md):
> 
> **Tarot cards theme**:
> - **Spirit**: Spirit awakening 
> - **Gamaliel**: Obsceno, desejos profundos

> [!quote] Factions 
> ```dataview
> table without ID link(file.link, name) AS "Faction", h + e + r as "Challenge", h as "H", e as "E", r as "R"
> from "nibiru/factions"
> WHERE contains(meta.category, "faction")=true
> sort id asc
> ```

> [!warning] Intro
> - 

> [!example] Sets

**Drone de manutenção**

- Os Vagabonds terminam de preparar o chumaço de cabos para o Hauler atravessar.
- A viagem começa e os Vagabonds vão à frente como scouts, junto de [VaelenSorra](../npcs/VaelenSorra.md) e [RheaArgyros](../npcs/RheaArgyros.md).
- Um drone de manutenção é visto a distância e, enquanto Conan corre para avisar a caravana, os demais se escondem.
- O drone, em uma posição ameaçadora procura pelos scouts, mas logo é distraído pela caravana e vai em direção à mesma.
- Conan está no caminho, mas se desvia para não ser atropelado pelo drone.
- Os **Enesu** armados na caravana começam a disparar contra o drone, mas mesmo assim ele consegue chega e esta pronto para atacar a caravana.
- Nesse instante Conan encontra uma barra de ferro no chão da estação e, em vários golpes rápidos, destrói o drone.
- Robert se lembra de seus conhecimentos de robótica, e do valor de guardar os destroços do drone. Ele convence [NabuaAmarud](../npcs/NabuaAmarud.md) de carregar os destroços na caravana.

![](https://i.imgur.com/6kddT09.png)    ![](https://i.imgur.com/sF47fFQ.png)

**Viagem e descobertas**

- Enquanto os scouts viajam pelo complexo de túneis dos Nexi da Penumbra, eles conversam com Vaelen e Rhea, e lembram-se de cenas em seus passados.
- Zumathi lembra-se do caminho até o o **Vault da Árvore da Família** - o lugar para qual estão indo, mas não lembra-se exatamente do local.
- Robert lembra-se de pessoas cultuando o **Devorador de Almas**, e a existência de uma relação com reduzir o tempo da estação desligada, entre as versões.
- Em conversa posterior com Vaelen, o acadêmico sugere que essa lembrança possa ser fictícia, dado que **Devorador de Almas** é o nome dado pelos **Enesu** (moradores da Penumbra) ao **Elevador V**. Esse nome é dado pois centenas de **Enesu** morreram durante a construção e continuam a morrer nos serviços de manutenção do **Elevador V**.

**Chegada no Vault da Árvore da Família**

- Os scouts chegam num imenso vault, redondo. O outro **Enesu** que estava junto deles volta à caravana para avisar do encontro.
- Eles se comunicam com alguém que os permite entrar e abre os portões.
- Dentro do vault eles caminham até uma vila, que fica ao pé de uma imensa árvore de metal com glóbulos azulados como flores imensas.
- Conan percebe que todos na vila se parecem com Robert, e termina por contar que ele provavelmente conheceu o pai de Robert (Edard), e que estava com ele quando morreu.
- Robert se lembra que essa árvore utiliza, de alguma forma, o fungo que ele coletou nos cabos dias atrás.
- Instantes depois, Zumathi se lembra de ter sido raptado durante uma manutenção do **Elevador V**. Nessa memória ele viu outros **Enesu** serem postos em uma câmara ritual ao lado da árvore, e dopados pelo fungo azul claro que encontraram antes. Depois de dopados, as raizes da árvore entravam pela boca dos **Enesu**, e eles seriam depois consumidos pela árvore.

![](https://i.imgur.com/kMDmmEU.png)


**Reunião da Família**

- Robert e Zumathi estão apavorados. Eles reconhecem o risco que correm por estar nesse vault.
- Suas memórias, em conjunto, criam um mapa do que pode estar acontecendo aqui: **Enesu** são raptados durante manutenções do **Elevador V** e trazidos para serem consumidos pela Árvore da Família. Enquanto isso, o clã Amarud traz seus membros para terem suas memórias absorvidas pela árvore. E os glóbulos azulados, grandes, contendo pessoas, produzem mais Vagabonds. É tudo muito confuso e, pior, maléfico.
- Enquanto isso, Rhea desaparece.
- E Conan conhece Arwia, a possível feiticeira que executa os rituais no vault. Arwia seria responsável por ajudar outros Vagabonds, mas também por operar o sistema da Árvore da Família.

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
