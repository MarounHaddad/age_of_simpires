# Age Of Simpires
A data mod for Age of Empires 2 Definitive Edition that attempts to add city building features to the base game.

The mod 

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

### 🛣️Stone Road

## ⚔️ Military Structures

### 🗼Fortified Tower

### 🏫Military Academy

### 🏯Fortress

### 🕳️Moat

### ⛓️Barricades

### 📍Impaled Prisoner

### Military Camp

## ⛩️Wonders

## 🌴Beautification


## ‼️ Known Issues
- houses after delete
- relic no longer in game
- 