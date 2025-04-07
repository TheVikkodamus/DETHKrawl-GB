# DethKrawl – Initiative System

This document explains how initiative works in DethKrawl and outlines the implementation for GB Studio. It includes standard, AGI-based tiebreakers, and simultaneous combat start options.

---

## Basic Initiative (Contested d6)

At the start of each combat encounter:

- Both the **player** and the **enemy** roll a **d6**
- The side with the **higher result** goes first
- If the result is **tied**, compare **AGI** as a tiebreaker
  - If AGI is also tied, both act **simultaneously**

---

## Standard Initiative Flow

1. Roll d6 for player
2. Roll d6 for enemy
3. Compare results:
   - Higher roll goes first
   - If tied:
     - Higher **AGI** wins
     - If AGI is tied → simultaneous turn

This version keeps things fast and adds value to AGI without full modifiers.

---

## Simultaneous Attack on Full Tie (Optional)

If both d6 rolls and AGI are tied:

- Both player and enemy take their actions
- **Damage is applied after both turns resolve**
- May result in both dying at once

Example:
> Player and enemy both roll a 4.  
> Both have AGI 2.  
> Player hits for 3. Enemy hits for 5.  
> Both drop to 0 HP. Both die.

---

## GB Studio Logic (Pseudocode)

### Variables:
- `VAR_INITIATIVE_PLAYER`
- `VAR_INITIATIVE_ENEMY`
- `VAR_PLAYER_AGI`
- `VAR_ENEMY_AGI`
- `VAR_PLAYER_DAMAGE`
- `VAR_ENEMY_DAMAGE`
- `VAR_PLAYER_HP`
- `VAR_ENEMY_HP`

### Step-by-Step

```
Set VAR_INITIATIVE_PLAYER = RANDOM(1, 6)
Set VAR_INITIATIVE_ENEMY = RANDOM(1, 6)

If VAR_INITIATIVE_PLAYER > VAR_INITIATIVE_ENEMY
    → Player Turn → Enemy Turn
Else If VAR_INITIATIVE_ENEMY > VAR_INITIATIVE_PLAYER
    → Enemy Turn → Player Turn
Else
    If VAR_PLAYER_AGI > VAR_ENEMY_AGI
        → Player Turn → Enemy Turn
    Else If VAR_ENEMY_AGI > VAR_PLAYER_AGI
        → Enemy Turn → Player Turn
    Else
        → Simultaneous Round:
            → Player Turn (store damage in VAR_ENEMY_DAMAGE)
            → Enemy Turn (store damage in VAR_PLAYER_DAMAGE)
            → Apply both damage values after turns
```

---

## Summary

| Rule                         | Description                                 |
|------------------------------|---------------------------------------------|
| Contested d6                 | Both roll, higher goes first                |
| Tie → AGI Tiebreaker         | Higher AGI wins                             |
| Full Tie → Simultaneous Turn| Both act, damage resolves after             |
| Optional AGI mod             | Adds tactics, avoids full randomness        |

This system makes AGI matter, keeps combat fast, and introduces tension through possible mutual death.
