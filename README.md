# DethKrawl

**A cursed dungeon-crawling OSR Game Boy game.**  
Inspired by *Mörk Borg*, *Deathbringer*, and the raw, pixel-scarred glory of retro handheld RPGs.

> Explore crypts, cast twisted magic, battle nightmares, and loot the rotting remains of civilization. You are no hero — just another corpse that hasn't fallen yet.

---

## Platform

- Built in **GB Studio** (Game Boy)
- Playable via ROM or browser (HTML5 export)
- No classes — your weapons, armor, and stats define your fate.

---

## Game Overview

- **Genre**: Dungeon-Crawling OSR RPG  
- **Setting**: The dying region of **Irezar**  
- **Core Loop**: Explore → Fight → Loot → Survive (or die)  
- **Inspiration**: Mörk Borg, Deathbringer, classic GBC RPGs  

---

## Character Creation

### Name Selector / Generator
- Players can input a name or generate a random cursed one

### Stat Allocation – 8 Points Total
Distribute 8 points across the following:

- **STR (Strength)** – Crush, lift, strike, grapple
- **AGI (Agility)** – Dodge, balance, swim, flee
- **PRE (Presence)** – Perceive, aim, charm, wield spells
- **TOU (Toughness)** – Resist poison, heal, survive falls

---

## Core Systems

### Difficulty Rating (DR)

**DR** determines how challenging a test or attack is.  
Most tests require a roll that meets or exceeds **12**.  
Modifiers such as **DR +2** increase the target number to **14**, and so on.  
All rolls use **d20 + relevant stat**.

---

### DethKrawler's Die
Each character has DethKrawler's die that is equal to the PC level. DethKrawler's Die can be spent to bend fate, 
allowing a character to use a pool of six-sided dice that respresents character's skill & luck.
Player may spend DethKrawler Die to: 
- Add to a TEST roll.
- Add a d6 to successful damge roll.
- Block d6 incoming damage.

Players may use multiple Deathbringer Dice on the same roll.
Players may not use Deathbringer Dice to alter a roll of natural 1.
Players may give one (1) DD to another player at any time.

Only PCs have Deathbringer Dice. NPCs and monsters do NOT have them.

---

## Starting Loot Tables

### D4 – Bag

| Roll | Result                        |
|:----:|-------------------------------|
| 1–2  | Nothing                       |
| 3    | Backpack (holds 7 items)      |
| 4    | Sack (holds 10 items)         |

---

### D6 – Gear

| Roll | Gear                              |
|:----:|-----------------------------------|
| 1    | Rope (30 feet)                    |
| 2    | PRE + 4 Torches                   |
| 3    | Random Unclean Scroll             |
| 4    | Medicine Chest (PRE +4 uses)      |
| 5    | Metal File and Lockpicks          |
| 6    | Bottle of Red Poison (d4 doses)   |

---

### D8 – Weapons

| Roll | Weapon         | Damage                        |
|:----:|----------------|-------------------------------|
| —    | Unarmed        | D2                            |
| 1    | Staff          | D4                            |
| 2    | Shortsword     | D4                            |
| 3    | Knife          | D4                            |
| 4    | Crossbow       | D6, PRE +5 bolts              |
| 5    | Warhammer      | D6                            |
| 6    | Sword          | D6                            |
| 7    | Bow            | D6, PRE +10 arrows            |
| 8    | Flail          | D8                            |

---

### D4 – Armor

| Roll | Armor Type     | Effect                                                                 |
|:----:|----------------|------------------------------------------------------------------------|
| 1    | No Armor        | None                                                                  |
| 2    | Light Armor     | Reduces damage by D2 (Tier 1)                                          |
| 3    | Medium Armor    | Reduces damage by D4 (Tier 2); DR +2 on AGI tests and DEF after the attack phase |
| 4    | Heavy Armor     | Reduces damage by D6 (Tier 3); DR +4 on AGI tests, DEF is DR +2        |

---

## Planned Features

- 8 cursed dungeons (e.g., The Moldbone Halls, Ashen Cathedral, Wyrm-Mouth Temple)
- Boss fights, traps, and randomly generated loot
- Unclean scrolls, relics, and consumables with unpredictable effects
- Top-down or first-person dungeon exploration
- Optional hotseat-style co-op

---

## Built With

- [GB Studio](https://www.gbstudio.dev)
- Game Boy resolution and palette
- Markdown and OSR design principles

---

## Development Status

**In development** — currently building the core loop, stat system, and loot engine.  
Targeting a vertical slice featuring:
- 1 dungeon
- 3 enemy types
- 1 boss
- Loot tables and character creation

---

## Contact

Want to contribute ideas, art, cursed weapons, or scroll effects?  
Open an issue or reach out directly.

