# DethKrawl – Mechanics Summary

## Core Resolution

- Roll `d20 + STAT` vs DR (Difficulty Rating)
- If the result is equal to or higher than DR → success
- Default DR is **12**, but it can shift based on the situation

## Stats

Each character has four stats:

- **STR** – Strength: melee, brute force, lifting
- **AGI** – Agility: dodging, stealth, defense
- **PRE** – Presence: awareness, ranged attacks, magic
- **TOU** – Toughness: survival, resistance, HP bonus

Roll `3d6` for each stat. Use the total to determine:

- Your **stat bonus** (used in most rolls)
- Your **passive chance of success** (`d6` behind-the-screen rolls by the GM)
- Your **spells per day** (only for characters who can cast)

| `3d6` Roll | Stat Bonus | `d6` Chance (GM behind screen) | Spells per Day |
|------------|-------------|-------------------------------|----------------|
| 3–5        | -1          | 1-in-6                        | —              |
| 6–10       | 0           | 2-in-6                        | +`d2`          |
| 11–14      | +1          | 3-in-6                        | +`d3`          |
| 15–17      | +2          | 4-in-6                        | +`d4`          |
| 18         | +3          | 5-in-6                        | +`d6`          |


> Sometimes, the GM will roll in secret to determine if a player **notices** or **reacts** to something without declaring an action — like spotting a trap, hearing footsteps, sensing danger, or intuiting a lie.
> Use the player's stat to determine their **passive success chance** on a `d6`.

**Examples of Passive Use:**
- **AGI**: Detecting a tripwire, reflexively dodging a sudden hazard
- **PRE**: Hearing whispers behind a door, noticing someone's lying
- **TOU**: Resisting fatigue, poison, or mind-altering fog
- **STR**: Bracing against sudden collapse or holding a door shut

> The GM rolls the `d6` behind the screen and only informs the player if something is noticed or resisted — or if it’s too late.

---

### Active vs Passive

- If a **player chooses to do something**, they roll a standard test:  
  `d20 + STAT` vs DR (usually DR12)
- If a **player is unaware** or not actively trying, the GM uses the passive `d6` chance.

> Use passive rolls to keep tension and surprise alive. If players always roll, they always suspect something is up.

---

## Advantage & Disadvantage

- **Advantage**: Roll `d20 + STAT +2`
- **Disadvantage**: Roll `d20 + STAT -2`

The GM applies these based on narrative positioning, tools, or environment.

## Health & Damage

- Starting HP = `2d6 + TOU`
- At 0 HP, fall unconscious for `TOU` rounds
- If not stabilized in time, make a **TOU test (DR14)**:
  - Success = gain a **Wound**, return with `d4` HP
  - Failure = death

## Death & Broken

If HP drops below zero again, roll `d20 + TOU` vs DR12:

- Success = **Broken** (roll on the Broken Table)
- Failure = **Dead**

When **Broken**, roll a `d6` to determine outcome (e.g., unconscious, wounded, or bleeding out). All rolls become DR16 until treated.

## Defense Rolls

When attacked, roll `d20 + AGI + Armor Bonus`:

- On failure = attack hits
- If you have Damage Reduction, roll and subtract that value from damage taken

## Combat

- **Melee Attack**: `d20 + STR` vs DR
- **Ranged Attack**: `d20 + PRE` vs DR
- **Spellcasting**: `d20 + PRE` vs DR

Critical (natural 20):
- x2 damage, downgrade enemy armor

Fumble (natural 1):
- Weapon breaks (attack)
- Double damage taken & armor reduced (defense)

## Encumbrance

- Carrying limit = `8 + STR` slots
- Bulky items = 2 slots
- Over capacity? Move limited to Close range and all AGI/DEF rolls are made at **DR +2**

## DethKrawler’s Die

You start with **1 DethKrawler Die per level** (`d6`s). You may spend one to:

- Add to a Test or Damage roll
- Block `d6` incoming damage

Cannot be used on a **natural 1**.  
You may gift one die to another player.

## Movement & Ranges

- Ranges are abstract: **Close**, **Near**, **Far**
- You may move one range band per turn unless hindered

## Recovery

**Short Rest**: Eat and drink → regain `d4` HP  
**Long Rest**: Eat, drink, and rest undisturbed → regain `d6` HP

No food or water = no HP recovery  
After 2 days without sustenance = lose `d4` HP per day

## Initiative

**Group**: GM and a player both roll `d6`; higher roll acts first  
**Individual**: Each player rolls `1d6 + AGI`, enemies roll `1d6`

## Cover

| Cover Type       | DR (No Armor) | DR (With Armor) |
|------------------|---------------|-----------------|
| No Cover         | 12            | 14              |
| Half Cover       | 10            | 12              |
| Three-Quarters   | 8             | 10              |
| Full Cover       | Cannot be targeted (unless flanked or hit by area effects)

## Kin (Optional Rule)

Characters are usually **Human**. Rare Kins such as **Firstborn** or **Infernal** exist and grant minor abilities. Referee may restrict their use.

---

This is the backbone of DethKrawl. The rest is rot, ruin, and whatever you bring to the table.
