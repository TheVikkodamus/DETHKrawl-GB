# DethKrawl – Core Mechanics

This document outlines the core gameplay mechanics of DethKrawl, including character stats, difficulty rating (DR), combat flow, and item interaction.

---

## Character Stats

Players allocate 8 points across four core stats:

- **STR (Strength)** – Physical power. Used for melee attacks, breaking objects, lifting heavy items, and grappling.
- **AGI (Agility)** – Speed and reflexes. Used for dodging, defending, balancing, and escaping.
- **PRE (Presence)** – Force of personality and focus. Used for aiming ranged weapons, perceiving danger, and wielding magic or scrolls.
- **TOU (Toughness)** – Endurance and resistance. Used to resist poison, survive falls, and recover health.

---

## Rolling Tests & Difficulty Rating (DR)

All tests use a roll of **1d20 + relevant stat**. The result must meet or exceed the **Difficulty Rating (DR)**.

- **Standard DR**: 12
- **Modifiers**: DR can increase depending on challenge (e.g., DR +2 = 14)

| DR Value | Challenge Level          |
|:----------:|:--------------------------|
| 10       | Easy                     |
| 12       | Standard                 |
| 14       | Hard                     |
| 16+      | Brutal                   |

---

## Combat System

Combat is turn-based with the following options:

- **Attack**: Roll d20 + STR (melee) or PRE (ranged) vs. enemy's DR
  - On hit, roll damage die (based on weapon) and subtract from enemy HP
- **Item**: Use scrolls, potions, gear, or tools
- **Run**: Test AGI to escape combat

Criticals and fumbles:
- **Natural 20**: Critical hit (max damage or special effect)
- **Natural 1**: Fumble (drop item, miss turn, etc.)

---

## Armor and Damage Reduction

Armor reduces incoming damage instead of improving hit chance.

| Armor Type     | Damage Reduction | Penalty                      |
|----------------|:------------------:|------------------------------|
| Light Armor    | D2               | None                         |
| Medium Armor   | D4               | **DR +2** to AGI and **DEF tests**   |
| Heavy Armor    | D6               | **DR +4** to AGI, **DEF is DR +2**   |

---

## Inventory & Items

- **Bag capacity** is determined at random (see loot tables)
- Items include:
  - Scrolls (one-time effects, cast using PRE)
  - Tools (lockpicks, ropes)
  - Consumables (torches, healing salves, poison)
- Weapons and armor affect how the player functions (no traditional classes)

---

## Co-op Support (Optional)

In hotseat mode, players alternate turns using shared or unique characters. Each may control a separate stat build or equipment set. Ideal for turn-based exploration and combat scenarios.

---

## Save & Death

- Game may use shrine saves or permanent death depending on difficulty setting [temporary]


---

For full loot details, see: `docs/loot-tables.md`
