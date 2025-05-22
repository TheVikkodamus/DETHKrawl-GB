# DethKrawl – Core Mechanics

This document outlines the core gameplay mechanics of DethKrawl, including character stats, difficulty rating (DR), combat flow, and item interaction.

---

## Character Stats

Roll `3d6` for each stat. Don’t record the total — just use the table to get a bonus.

| `3d6` Roll | STAT Bonus | `d6` chances [GM roll behind screen]| Spell per Day|
|:---:|:---:|:---:|:---:|
| 3–5  | -1 | 1-in-6| |
| 6–10 | 0  | 2-in-6| +`d2` per day|
| 11–14  | +1 | 3-in-6| +`d3` per day|
| 15–17  | +2 | 4-in-6| +`d4` per day|
| 18     | +3 | 5-in-6| +`d6` per day|

Assign to:

- **STR** – *Smash, lift, hack*  
- **AGI** – *Dodge, sneak, escape*  
- **PRE** – *Spot, aim, cast*  
- **TOU** – *Resist, heal, survive*
---

**Roll `d20` + STAT ≥ DR**  
- Default DR (difficulty rating) is **12**  
- Enemies roll flat **`d20`**, no stat

### Difficulty Ratings

| DR | Challenge   |
|:---:|:---:|
| 6  | Trivial     |
| 8  | Routine     |
| 10 | Skilled     |
| 12 | Pressured   |
| 14 | Tough       |
| 16 | Heroic      |
| 18 | Impossible? |

### Combat Difficulty Rating

- **Melee**: `d20` + STR vs DR12  
- **Ranged**: `d20` + PRE vs DR12  
- **Spells**: `d20` + PRE vs DR12

---

### Advantage vs Disadvantage

**Advantage**  
You gain an Advantage when:

- You attack by surprise or from behind  
- You fire a ranged weapon from an elevated position  
- You use the right tools for the job  

The **Game Master** may also award Advantage when the fiction favors the player.

> When rolling with Advantage, roll **d20 + STAT +2** vs DR.


**Disadvantage**  
You suffer a Disadvantage when:

- The terrain is slippery or unstable  
- You lack the right tools for the task  

The **Game Master** may assign a Disadvantage when the fiction works against the player.

> When rolling with Disadvantage, roll **`d20` + STAT -2** vs DR.

---

### Health

Start with `2d6` + **TOU** HP.  

When it hits 0 — **you are unconscious.** for **TOU** rounds. If no **player character** stabilizes the unconscious player character. The player will have to roll as they have negative HP.  If they die. Another fool will take their place.

#### Broken

### Broken `d6` Table

| `d6` Roll | Result                                                                 |
|---------|------------------------------------------------------------------------|
| 1–2     | Fall unconscious for **d4** rounds, awaken with **`d4`** HP.             |
| 3–4     | Roll on the **Wounds Table**, then become active with **`d4`** HP.       |
| 5–6     | **Bleeding out**: death in **`d4`** hours unless treated.                |

All tests are DR16 until you are treated.

---

### Wounds Table (d66)

Roll `d66` (roll two `d6` dice, one for tens, one for ones) and consult the table:

| d66 | Scar Description                                      |
|-----|--------------------------------------------------------|
| 11  | A jagged scar runs from your cheek to your jaw.       |
| 12  | Burned fingertips — blistered, blackened, or melted.  |
| 13  | Deep bite marks on your forearm — still slightly swollen. |
| 14  | A missing eyebrow, never grew back right.             |
| 15  | A cracked tooth or two — smile with caution.          |
| 16  | Scar across the throat — close call.                  |
| 21  | Split nose — crooked and lumpy.                       |
| 22  | Ear partially torn off — frayed like paper.           |
| 23  | Knife gash down the thigh — stitched with wire.       |
| 24  | Missing pinky finger — bitten, not cut.               |
| 25  | Eyelid twitches from an old head wound.               |
| 26  | Puncture wound on the ribs — never quite healed right.|
| 31  | Torn lip — leaves a permanent snarl.                  |
| 32  | Blistered neck from acid splash.                      |
| 33  | Hook scar in the shoulder — jagged and round.         |
| 34  | Long scratch across the back — claw or blade?         |
| 35  | Scalp wound — part of your hair no longer grows.      |
| 36  | Scarred knuckles from too many close fights.          |
| 41  | Ribcage burns — marked like coals.                    |
| 42  | Circular scar on the palm — ritual or accident?       |
| 43  | Torn calf muscle — limps slightly in the rain.        |
| 44  | Branding mark — faded but visible.                    |
| 45  | Cratered scar on the hip — bone shows when bent.      |
| 46  | Eye socket bruised forever — eye still intact.        |
| 51  | Crosshatch scars over your back — like a whip's kiss. |
| 52  | Burned scalp under your helmet.                       |
| 53  | Cheekbone dented — it clicks when you chew.           |
| 54  | Scar across the collarbone — almost bled out.         |
| 55  | Crooked jaw — reset by a friend, not a healer.        |
| 56  | Bruised temples — damage from unseen force.           |
| 61  | Finger permanently bent — bad heal from a break.      |
| 62  | Gash across the chest — just missed the heart.        |
| 63  | Ear pierced through by a blade — hole still open.     |
| 64  | Scar shaped like a rune — but you don’t know why.     |
| 65  | Torn lip and cheek — shows your teeth when you grin. |
| 66  | One eye clouded and gray — vision mostly intact.      |

---

## DethKrawler’s Die

You begin with **1 DethKrawler Die per level**. These are **`d6s`** that bend fate.

You may spend one to:

- Add to a **Test** roll  
- Add to a **Damage** roll  
- **Block `d6`** incoming damage

> - Spend **multiple dice** if you want.  
> - **Cannot** be used on a **natural 1** — **failure is absolute**.  
> - You may **gift 1 die** to another player at any time.


## Combat

1. Combat Rounds
2. Initiative
3. Movement (Near, Range, Far)
4. Rolling to-hit vs DR (Difficulty Rating)
5. Rolling damage or damage reduction

### Attack Phase

- The **player declares** their target and describes the type of attack:
  - **Melee Attack**: Uses `STR`, unless the weapon is tagged with *Finesse* — then `AGI` may be used.
  - **Missile Attack**: Uses `PRE`.
- The player rolls `d20 + relevant STAT`.
  - If the result **meets or exceeds the Difficulty Rating (DR)**, the attack hits.

---

### Defence Phase

- The **GM declares** which enemy is attacking and what kind of attack it is.
- The **player rolls** `d20 + AGI + Armor Bonus` (if any) to defend.
  - If the roll **fails**, the attack hits.
  - If the character has **Damage Reduction**, they may roll it now:
    - Subtract the **Damage Reduction roll** from the incoming damage.
    - Record the remaining damage on the character sheet.

---

#### Black Powder Weapons V Armor

> These weapons are deadly and dangerous, it will ignore all amor. 
> A black powder weapon takes one round to reload after it is fired,
> and you cannot reload when in melee range of a foe.

--- 

#### Crit (Natural 20)

- **Attack**: X2 damage and armor reduced 1 tier.
- **defence**: PC gets a free attack.

### Fumble (Natural 1)
- **Attack**: Weapon Breaks.
- **defence**: PC takes double damage, armor is reduced one tier. 

---

### Cover

PCs and Enemies may take or use cover; the quality of cover raises the DR (difficulty rating) to hit. 

A player character is using cover, their difficulty rating will go down: 

- No Cover: DR12 | DR14 (*medium/heavy armor*)
- Half-Cover: DR10 | DR12 (*medium/heavy armor*)
- Three-Quarters: DR8 | DR10 (*medium/heavy armor*)
- Full Cover: The PC can't be targeted. Unless they are **flanked** or affected by an **area effect attack**. 
 
### DEATH

When a player character's Hit Points have been reduced to negative HP. Roll `d20` + TOU DR12.

- On a success = **BROKEN**.
- On a fail, you are **DEAD**. 

GM or a Broken player character can roll at the broken table (`d6`).

#### Broken

### Broken `d6` Table

| `d6` Roll | Result                                                                 |
|---------|------------------------------------------------------------------------|
| 1–2     | Fall unconscious for **d4** rounds, awaken with **`d4`** HP.             |
| 3–4     | Roll on the **Wounds Table**, then become active with **`d4`** HP.       |
| 5–6     | **Bleeding out**: death in **`d4`** hours unless treated.                |

All tests are DR16 until you are treated.
