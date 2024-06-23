---
name: The Amarud
game_date: v4 c500 d79
pcs: "Conan, Robert, Zumathi"
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
> - [Conan](../pcs/Conan.md):
> - [Robert](../pcs/Robert.md):
> - [Zumathi](../pcs/Zumathi.md):
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

- Imediatamente antes de abrirem a porta to alçapão vocês percebem um homem dormindo ao lado de vocês. Ele é Zumathi, também um Vagabond. Vocês juntos conseguem abrir a porta e sair do poço que os aprisionou por tanto tempo.

- **Descrição do Ambiente ([OutbackNexus](../locations/OutbackNexus.md))**:
	- O **teto** está pontilhado de luzes **piscantes** e faíscas ocasionais de fiações expostas.
	- O ar está cheio de um **zumbido** baixo e constante de **maquinário** e ecos distantes de veículos de transporte em movimento.

![](https://i.imgur.com/PxIZfJk.png)

- **Encontro com Vaelen Sorra**: Você encontra [Vaelen Sorra](../npcs/VaelenSorra.md), o estudioso exilado, fora da construção em ruínas.
	- Ele fornece informações enigmáticas sobre a área e dá pistas sobre conhecimentos valiosos escondidos nas profundezas da estação. Ele parece falar muitos idiomas e se comunica com você em Dopomac.
	- Vaelen alerta que os Vagabundos nunca devem revelar a outros sua condição de amnésicos, pois amnésicos são caçados para experimentos na estação.
	- Ele explica que a estação possui versões, que são ciclos longos isolados uns dos outros por décadas de desligamento. Cada um desses ciclos é governado por diferentes sociedades. Os ciborgues de borracha que você enfrentou no poço parecem ser de uma versão anterior.
	- Vaelen leva você até sua amiga Rhea, que está montando acampamento para sua caravana no Nexus vizinho.

![](https://i.imgur.com/g98dene.png)

> [!example] Sets

- **Terrenos Baldios Industriais**
- Encontro com [Rhea Argyros](../npcs/RheaArgyros.md), amiga de Vaelen
- Rhea explica que estão explorando para uma caravana de Enesu em uma missão importante.
- Vocês se oferece para ajudar, mas estão **extremamente exaustos**. Após montar os sacos de dormir para o sono subaquático, apenas Zumathi continua ajudando Rhea, os demais dormem.
	- Dormir debaixo d'água isola o zunido e diminui o desconforto da gravidade mais alta.

![](https://i.imgur.com/LSktpcm.png)


- **Rhea acorda vocês** Dormiram bem?
	- A caravana chega e cerca de 200 pessoas terminam de montar o acampamento.
	- Cerca de 8 carregam armas leves, a caravana não parece preparada para nenhuma ação extremamente violenta.
	- Depois que todos terminam seus trabalhos, juntam-se para jantar.
	- Zumathi conversa com [Tauthe](../npcs/Tauthe.md), que explica que vão ter que cortar o chumaço de cabos para o hauler atravessar. Essa tarefa poderia contar com a ajuda dos Vagabonds.

![](https://i.imgur.com/qyPKXXx.png)

- **Encontro com [NabuaAmarud](../npcs/NabuaAmarud.md)**
	- Vocês finalmente são apresentados a Nabua, que sai de dentro do Hauler.
	- Nabua explica que estão numa missão para encontrar Arwia. Arwia saberia do paradeiro de uma terceira pessoa, e essa procura seria uma missão subsequente, caso Arwia seja encontrada. Ele oferece $\mathbb{N}$ 200 (Nibirollars) para a primeira missão, além de comida e estadia com a caravana.

![](https://i.imgur.com/309znJG.png)

- **Chumaço de cabos**
	- Vocês trabalham com Tathue e sua equipe, e cortam cabos de comunicação, estruturais, linhas de óleo e eletricidade.
	- Todos tomam cuidado com poças de água, evitando choques.
	- Vocês encontram uma área com crescimento de um fungo azul claro.
	- Um dos trabalhadores está interessado e experimenta o fungo.
	- Vaelen, que está com seu tablet conectado em um cabo de comunicação cortado, diz que esse fungo pode ser alucinógeno.
	- Minutos depois, o trabalhador que provou o fungo ataca um de seus colegas, cortando o nariz. Robert atira na perna dele, e os demais o seguram e amarram.

![](https://i.imgur.com/MbxsRwe.png)


> [!bug] Random encounters

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
