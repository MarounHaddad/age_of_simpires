# Age Of Simpires
A data mod for Age of Empires 2 Definitive Edition that attempts to add city building features to the base game.

The mod adds more emphasis on building and expanding the city. For that end, the house population capacity was dropped to 2 pop per house. New building maintenance mechanic, as well as health and crime management, force the player to lay the city in a more structured and thoughtful way.

The mod also introduces a small cast system for training the unique units as well as new military structures and concepts such as buildings that cost food, temporary buildings, and structures that cost `unit kills`.

New buildings were added with graphics for the different architecture with a standardized generic destruction animation.

A new menu mechanic enables extending the villager menu to include the new structures as well as enabling some of the `In Editor` only buildings.

⚠️*The mod was lightly tested and most probably introduces some unintended behavior or even bugs to the base game*

[TOC]

## 🏴 Menu Selector

The player can place a "Menu Selector" that will allow them to switch between multiple different menus to build different types of structures:

- Governance
- Military Structures
- Wonders
- Beautification

The "Menu Selector" is in the 12th position of the main menu (replaces the "Wonder" button). It has the graphic of a flag.
It costs 0 resources to build and can be built multiple times.

Once the "Menu Selector" is built, the *SIM* effects will activate. This is to prevent the SIM effects from affecting the AI player.
The AI will maintain a standard game to an extent.

## 🏛️Governance
This menu will allow the player to place buildings related to the maintenance of the health and security of the houses as well as other civic buildings.

The list of buildings includes:
- Maintenance
- Apothecary Shop
- Guards Station
- Tax Collector
- Trade Workshop
- Stone Road
- Manor

### 🔨Maintenance
*Cost: 50 wood*

The health of some buildings will degrade over time until they are destroyed. 

This feature is activated when the `Menu Selector` flag is placed!

The following buildings will degrade unless maintained:
- House
- Market
- Monastery
- Trade Workshop
- University
- Fortified Church
- Feitoria
- Caravanserai
- Apothecary Shop
- Guards Station
- Tax Collector
- Manor
- Military Academy

The player can build a `Maintenance` building that will automatically fix the surrounding buildings in a rage of "7 tiles".

If any part of the building that is deteriorating is within the range, the building is gradually repaired and maintained.

### 🏥Apothecary Shop
*Cost: 50 wood*

The houses will become diseased if they are not served by an `Apothecary Shop`.

This feature is activated when the `Menu Selector` flag is placed!

Once the `Menu Selector` is placed, a counter will start (this will show as a health bar on the lower corner of the building).

Once the health bar is depleted, the house will be diseased. This is indicated by a green puddle that will show up in the lower corner of the house.

A diseased house will degrade the health of surrounding citizens (villagers, tax collectors and guards) in a range of "4 tiles".

The diseased house will recover again after a period (the recovery time is also shown by a health bar above the disease puddle).

To prevent the houses from getting diseased, and to quickly recover diseased houses, the player can place an `Apothecary Shop` in the vicinity of the house.

The `Apothecary Shop` will heal all nearby houses (in a range of "7 tiles") and prevent them from getting diseased.

> The range of the Apothecary Shop should cover the lower corner of the house for the healing to take affect, otherwise, even if the house is within the range but its lower corner is not covered, the house can still get diseased.

#### 👨‍⚕️Healer
*Cost: 100 Food*

The `Apothecary Shop` allows the player to train `Healers`. 

A `Healer` is a citizen unit that can only heal nearby citizens. It is similar to a priest, however, it can only heal other units. It cannot convert enemy units.

### 🛡️Guards Station
*Cost: 50 wood*

The houses will produce criminals if they are not served by a `Guards Stations`.

This feature is activated when the `Menu Selector` flag is placed!

Once the `Menu Selector` is placed, a counter will start (this will show as a health bar on the lower corner of the building).

Once the health bar is depleted, the house will spawn a criminal. The criminal will attack nearby citizens.

To prevent the houses from spawning criminals, the player can place a `Guards Stations` in the vicinity of the house.

The `Guards Station` will serve all nearby houses within a range of "8 tiles"

> The range of the Guards Station should cover the lower corner of the house for the healing to take affect, otherwise, even if the house is within the range but its lower corner is not covered, the house can still spawn a criminal.

#### 💂Guard
*Cost: 50 Food*

The `Guards Station` allows the player to train a `Guard`.

The guard is a cheap unit that can only fight criminals. It cannot be used against other military units.

You can set it to patrol the streets for protection.

### 🏦Tax Collector
*Cost: 100 Wood*

Houses will have an amount of gold stored in them once built:
- Dark Age: 12 Gold
- Feudal Age: 15 Gold
- Castle Age: 20 Gold
- Imperial Age: 25 Gold

However, the house cost also increases per age:
- Dark Age: 25 Wood
- Feudal Age: 30 Wood
- Castle Age: 35 Wood
- Imperial Age: 50 Wood

#### 💰Tax Collector Official
*Cost: 50 Food*

The `Tax Collector` allows the player to train a `Tax Collector official`.

This unit can collect the taxes from the houses and deposit them in the Town center. It collects the taxes at a rate of `1` per trip.

The `Tax Collector official` has to be within the range of the `Tax Collector` building for him to be able to operate.

### 🏪Trade Workshop
*Cost: 250 Wood 50 Stone*

Generates `Food` passively. Around 1 Food per 5 seconds (in game time).

### 🏡Manor
*Cost: 110 wood*
*Provides: 5 Population*

The `Manor` is a housing unit that enables the player to train the Castle unique units as well as the units in the knight line.

This unique units requirement for a manor is enabled when the `Menu Selector` flag is placed!

The `Manor` also requires maintenance as well as health and crime management. However, to prevent the `Manor` from getting diseased, the player has to build a `university` in its vicinity. Furthermore, to prevent the `Manor` from spawning a criminal, the player has to build a `Monastery\Fortified Church` in its vicinity.

- The `university` will serve all nearby manors within a range of "8 tiles" 
- The `Monastery` will serve all nearby manors within a range of "7 tiles" 

The following units require a manor to be trained:
Knight, Cavalier, Paladin, longbowman, Cataphract, Woad Raider, Chu Ko Nu, Throwing Axeman, Huskarl, Samurai, Mangudai, War Elephant, Mameluke, Teutonic Knight, Janissary, Berserk, Jaguar Warrior, Tarkan, War Wagon, Plumed Archer, Conquistador, Kamayuk,  Elephant Archer, Genoese Crossbowman, Magyar Huszar, Boyar, Camel Archer, Shotel Warrior, Gbeto, Organ Gun, Arambai, Ballista Elephant, Karambit Warrior, Rattan Archer, Konnik, Kipchak, Leitis, Keshik, Coustillier, Serjeant, Hussite Wagon,  Obuch, Ratha,  Urumi Swordsman, Chakram Thrower, Ghulam, Centurion, Monaspa, Composite Bowman, Savar, Iron Pagoda, Liao Dao, White Feather Guard, Tiger Cavalry, Fire Archer, Sun Jian, Kona, Guecha Warrior,Blackwood Archer

*The manor does not provide any taxes*

### 🛣️Stone Roads
*Cost: 3 stone*

The `Stone Roads` allow unit to move faster on them.

The speed of the units is increased by the following rates:
- Civilian: 1.3
- Infantry: 1.2
- Archers: 1.2
- Cavalry: 1.2
- Scout: 1.2
- Siege weapons: 1.3
- Monk: 1.2
- Monk With Relic: 1.1
- Healer: 1.2
- Trade Cart: 1.3
- War Elephant: 1.2
- Elephant Archer: 1.2
- Phalanx: 1.2
- Hero: 1.2
- Petard: 1.2
- Cavalry Archer: 1.2
- Hand Cannoneer: 1.2
- Two Handed Swordsman: 1.2
- Pikeman: 1.2
- Spearman: 1.2
- Raider: 1.2
- Cavalry Raider: 1.2
- King: 1.2
- Packed Unit: 1.3
- Controller Animal: 1.2
- Domestic Animal: 1.2
- Livestock: 1.2
- Prey Animal: 1.2
- Predator Animal: 1.2

## ⚔️ Military Structures
This menu will allow the player to place units related to military structures:

- Fortified Tower
- Military Academy
- Fortress
- Moat
- Barricades
- Impaled Prisoner
- Military Camp

### 🗼Fortified Tower
*Cost: 150 stone 100 wood*

The `Fortified Tower` is a hero building that is not buildable in the base game. It is immune to conversion and can regenerate hit points.

### 🏫Military Academy
*Cost: 200 wood*

The `Military Academy` is a building that allows the player to train new special military units:
- General
- Poison Siege Onager

#### 🎖️General
*Cost: 100 Gold 100 Food*

The `General` is a hero unit that boosts the attack rate of the nearby units making them more effective. It cannot fight and only acts as a support for the nearby units within a range of 4 tiles.

Only the player's units are effected.

As a hero unit, the `General` regenerates hit points.

The `General` boosts the reload time/attack rate of the following units as follows:
- Infantry: 0.166667
- Archers: 0.166667
- Cavalry: 0.166667
- Conquistador: 0.166667
- War Elephant: 0.166667
- Elephant Archer: 0.166667
- Phalanx: 0.166667
- Petard: 0.166667
- Petard: 0.166667
- Cavalry Archer: 0.166667
- Hand Cannoneer: 0.166667
- Two Handed Swordsman: 0.166667
- Two Handed Swordsman: 0.166667
- scout: 0.166667
- Pikeman: 0.166667
- Spearman: 0.166667
- Raider:  0.166667
- Cavalry Raider:  0.166667

#### ☠️Poison Siege Onager 
*Cost: 135 Gold 160 Food*

This is a siege onager that launches a `Dead Cow` as a projectile. The dead cow will act similar to the disease goo and poison nearby units degrading their health.

*This unit is a reference to some accounts of early biological warfare where dead animals were catapulted into besieged towns to create discomfort and maybe disease.*

### 🏯Fortress
Different civilizations can build unique castles currently only available in the Editor.

**Fortress**
*Cost: 200 Wood 400 Stone*
*Available for: Western European Civs*

**Wooden Fort**
*Cost: 400 Wood 200 Stone*
*Available for: Meso Civs, Andes Civs*

**Poenari Castle**
*Cost: 1000 Stone*
*Available for: South European Civs, Slavic Civs, Eastern European Civs*

**Large Fort(New Building)**
**Cost: 1000 Stone**
*Available for: Oriental Civs, Indian Civs, Central Asian Civs, African Civs, Byzantines*

#### 👑Emperor In Litter
**Cost: 100 Gold** 

Can be trained in the Fortress/Poenari Castle/Large Fort/Woodend Fort. One unit can be trained per Fort.
The unit boosts the work rate of nearby units.

### 🕳️Moat
*Cost: 5 Wood 5 Stone*

`Moats` are structures that can slow down units traversing them. 

The affect the speed of units traversing them as follows:
- Civilian: 0.5
- Infantry: 0.5
- Archers: 0.5
- Cavalry: 0.3
- Scout: 0.3
- Siege weapons: 0.1
- Ballista: 0.1
- Monk: 0.5
- Monk With Relic: 0.3
- Healer: 0.5
- Trade Cart: 0.1
- War Elephant: 0.1
- Elephant Archer: 0.1
- Phalanx: 0.1
- Hero:  0.3
- Petard: 0.2
- Cavalry Archer: 0.3
- Hand Cannoneer: 0.4
- Two Handed Swordsman: 0.4
- Pikeman: 0.4
- Spearman: 0.4
- Raider: 0.3
- Cavalry Raider: 0.3
- King: 0.3
- Packed Unit: 0.1
- Controller Animal: 0.3

*The speed of all units including the owner player of the moat is affected by the moat*

### ⛓️Barricades
*Cost: 5 Wood 3 Stone 5 Gold*

`Barricades` are structures that slow down and inflict damage to units passing through them. 

- All units are slowed down by 0.9
- Siege units hit points are not affected by barricades, only speed
- The HP of the villagers building the barricades is not affected, enemy villagers are effected however.
- The damage (degenerating health) will take effect as long as the unit is in contact with the barricades.

### 📍Impaled Prisoner
*Cost: 50 Wood 50 Gold 1 Killed Unit*

An `Impaled Prisoner` is a structure that decreases the attack rate/reload time of nearby enemy units.

Every `Impaled Prisoner` structure requires **1 kill** besides the other resources.

The structure reduces the attack rate/reload time of nearby enemy units as follows:
- Civilian: -1.3
- Infantry: -1.16667
- Archers: -1.16667
- Cavalry: -1.16667
- Scout: -1.16667
- War Elephant: -1.16667
- Elephant Archer: -1.16667
- Phalanx: -1.16667
- Petard: -1.16667
- Cavalry Archer: -1.16667
- Hand Cannoneer: -1.16667
- Two Handed Swordsman: -1.16667
- Pikeman: -1.16667
- Spearman: -1.16667
- Raider: -1.16667
- Cavalry Raider: -1.16667

### 🏕️Military Camp
*Cost: 100 Wood 20 Gold 50 Food*

The `Military Camp` is a **temporary** structure that heals nearby units. The structure HP will degrade gradually until it is destroyed.

## ⛩️Wonders

The wonders menu enables the player to build the main *Wonder* of each civilization besides other wonders that are not buildable by default in the game.

- **Sankore Madrasah**: Malians
- **Rock Church**: Ethiopians

- **Sanchi Stupa**: Indian civs
- **Gol Gumbaz**: Indian civs

- **Cathedral**: Western European civs
- **Quimper Cathedral**: French
- **Tower of London**: Britons
- **Aachen cathedral**: East European civs
- **Dormition Cathedral**: Slavic civs

- **Hall of Heroes**: East Asian civs, South East Asians civs
- **Temple of Heaven**: Chinese

- **Mosque**: Oriental civs, Central Asian civs
- **Dome of the Rock**: Oriental civs

- **Minaret of Jam**: Central Asian civs

- **Amphitheatre**: South Europeans
- **Arch of Constantine**: South Europeans
- **Aqueducts**: South Europeans
- **Colosseum**: Italians, Romans

## 🌴Beautification

The beautification menu allows the player to build structures that embellish their city such as:
- 🗿**Statues**
- 🏺**Columns**
- ⛲**Fountains**
- 💐**Gardens** New structure that is unique per architecture set with 14 different graphics each.

## ‼️ Known Issues
- The houses when destroyed or deleted are not decaying completely and remain on the map. This keeps the visibility enabled for the player even after the house is destroyed. Most probably caused by the objects that enable the health and crime effects.

- For the houses to spawn criminals the relic and monk carrying relic had to be altered which eliminated the relic from the game. Now criminals will spawn across the map where relics used to spawn.

- The new structures and buildings enabled by the mod are not age bound. The player can build advanced structures like the fortresses and the fortified towers even in Dark Age.