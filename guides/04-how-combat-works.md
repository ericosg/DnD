# How Combat Works — The Turn-by-Turn Breakdown

If you've played any turn-based RPG, tabletop combat will feel familiar. It's the same core loop — just without a computer doing the math for you.

---

## Starting Combat: Initiative

When a fight breaks out, everyone rolls **initiative** to determine turn order.

**Initiative = d20 + DEX modifier**

The DM rolls initiative for all enemies. Everyone's rolls are ranked from highest to lowest — that's the turn order for the entire fight. It doesn't change unless a special ability modifies it.

> Some feats and features can boost your initiative further. The **Alert** feat, for example, adds +5 to initiative rolls.

---

## Your Turn: The Action Economy

On each of your turns, you get:

| Resource | What It Is | Examples |
|---|---|---|
| **1 Action** | Your main thing | Attack, Dash, Dodge, Hide, Use an Object, Cast a Spell |
| **1 Bonus Action** | A smaller thing (only if an ability grants one) | Off-hand attack (dual wielding), certain class features, some spells |
| **Movement** | Move up to your speed (usually 30 ft.) | Walk, climb, swim. You can split movement before and after your action. |
| **1 Free Interaction** | A tiny thing | Open a door, draw a weapon, shout a warning |
| **1 Reaction** | A response on someone else's turn (once per round) | Opportunity attack, the Shield spell, certain class features |

### Example Turns by Class

What a combat turn looks like depends on your class. Here are three examples:

**Fighter (melee)**
1. **Move** 20 ft. to reach the nearest enemy.
2. **Action:** Attack with your longsword. Roll d20 + STR + proficiency. If you hit, roll 1d8 + STR for damage. At level 5, you get **Extra Attack** and swing twice.
3. **Bonus Action:** If you have the Two-Weapon Fighting style and a light weapon in your off hand, make a second attack. Otherwise, you may not have a bonus action to use — that's fine, not every class uses one every turn.
4. **After your turn:** If an enemy moves away from you, use your **Reaction** for an opportunity attack.

**Rogue (melee)**
1. **Move** 15 ft. to flank the enemy.
2. **Action:** Attack with your shortsword. Roll d20 + DEX + proficiency. If you hit and have advantage (or an ally is adjacent to the target), add **Sneak Attack** damage.
3. **Bonus Action:** You have a choice — attack with an off-hand weapon for a second chance at Sneak Attack, or use **Cunning Action** to Hide or Disengage. This is the Rogue's core tactical decision each turn.
4. **After your turn:** If an enemy moves away from you, you can use your **Reaction** for an opportunity attack.

**Wizard (spellcaster)**
1. **Move** 10 ft. back to stay out of melee range.
2. **Action:** Cast **Burning Hands** (1st-level spell, 15 ft. cone). Each creature in the area makes a DEX saving throw. On a failure, they take 3d6 fire damage; on a success, half.
3. **Bonus Action:** Cast **Misty Step** (bonus action spell) to teleport 30 ft. to safety behind cover. Note: if you cast a spell as a bonus action, the only spell you can cast with your action is a cantrip.
4. **Reaction (later in the round):** An enemy's attack hits you. Cast **Shield** to boost your AC by +5, potentially turning the hit into a miss.

---

## Making an Attack Roll

1. Roll **d20**
2. Add your **ability modifier** (STR for melee, DEX for ranged or finesse weapons)
3. Add your **proficiency bonus** (if you're proficient with the weapon)
4. Compare to the target's **AC (Armor Class)**
5. **Meet or beat AC = hit. Under = miss.**

> Example at level 1 with a +3 ability modifier and +2 proficiency: d20 + 5.
> Against an enemy with 15 AC, you need to roll a 10 or higher. That's a 55% chance.

### Critical Hits and Misses

- **Natural 20** (the die shows 20): Automatic hit, **double all damage dice** (not modifiers).
- **Natural 1** (the die shows 1): Automatic miss, regardless of modifiers. Some DMs add comedic fumble effects, but by RAW (Rules As Written) it's just a miss.

---

## Damage

When you hit, you roll damage. The formula depends on your weapon:

**Melee weapon:** weapon dice + ability modifier (usually STR or DEX)
**Ranged weapon:** weapon dice + DEX modifier
**Spell:** as described in the spell (no ability modifier unless the spell says so)

Some examples:
- **Longsword:** 1d8 + STR modifier
- **Shortsword (finesse):** 1d6 + DEX modifier
- **Longbow:** 1d8 + DEX modifier
- **Fire Bolt (cantrip):** 1d10 (no modifier)

Class features can add more damage — a Rogue's Sneak Attack, a Paladin's Divine Smite, a Barbarian's Rage bonus, etc.

---

## Dual Wielding Rules

If your character fights with two weapons:

1. When you take the **Attack action** with a **light melee weapon** in one hand, you can use your **bonus action** to attack with a different **light** weapon in the other hand.
2. Both weapons must have the **light** property. Shortswords, scimitars, daggers, and handaxes all qualify.
3. You **don't add your ability modifier to the off-hand damage** (unless you have the Two-Weapon Fighting fighting style).
4. You can draw both weapons on the same turn using your free interaction (some DMs are strict about this — technically drawing two weapons requires two interactions. Ask your DM).

---

## Conditions You'll See Often

| Condition | Effect | How You Get It |
|---|---|---|
| **Prone** | Disadvantage on attacks. Melee attacks against you have advantage, ranged have disadvantage. | Knocked down, tripped |
| **Restrained** | Speed 0, disadvantage on attacks, attacks against you have advantage | Nets, grapples, Web spell |
| **Poisoned** | Disadvantage on attack rolls and ability checks | Poison, some monster abilities |
| **Frightened** | Disadvantage on checks/attacks while you can see the source, can't move closer to it | Dragon fear, spells |
| **Incapacitated** | Can't take actions or reactions | Some spells, being stunned |
| **Stunned** | Incapacitated + can't move + auto-fail STR/DEX saves + attacks against you have advantage | Monk's Stunning Strike, some spells |
| **Unconscious** | Out cold. Auto-fail STR/DEX saves, attacks have advantage, melee hits are auto-crits | Dropping to 0 HP, Sleep spell |

---

## Dropping to 0 HP — Death Saves

When your HP hits 0, you don't die instantly. You fall **unconscious** and start making **death saving throws** at the start of each turn.

- Roll a d20. No modifiers.
- **10 or higher** = success
- **9 or lower** = failure
- **3 successes** = you stabilize (unconscious but no longer dying)
- **3 failures** = you die
- **Natural 20** = you wake up with 1 HP
- **Natural 1** = counts as 2 failures

If an ally heals you (even 1 HP), you wake up immediately and your death saves reset. This is why having a healer in the party matters.

> Every character goes down sometimes. Play smart — use the Dodge or Disengage actions when things get dangerous, use cover, and don't stand in the open trading blows if you can't take the hits. Know when to fight and when to reposition.

---

## Common Combat Actions (Beyond Attacking)

| Action | What It Does | When to Use It |
|---|---|---|
| **Dash** | Double your movement for the turn | Running away, closing distance |
| **Disengage** | Your movement doesn't provoke opportunity attacks | Escaping melee safely |
| **Dodge** | All attacks against you have disadvantage, you have advantage on DEX saves | You're surrounded and need to survive a round |
| **Hide** | Make a Stealth check. If you beat enemies' passive Perception, you're hidden | Setting up advantage for your next attack |
| **Help** | Give an ally advantage on their next check or attack | When your attack isn't as useful as helping a heavy hitter |
| **Ready** | Prepare an action with a trigger ("When the goblin opens the door, I attack") | Ambushes, coordinated plans |

These actions are available to every character. Some classes get features that make certain actions more efficient — for example, a Rogue's Cunning Action lets them Dash, Disengage, or Hide as a bonus action instead of their main action.

---

## Opportunity Attacks

When a creature **moves out of your melee reach** (5 ft. for most weapons), you can use your **reaction** to make one melee attack against them. This is free — it doesn't cost your action.

This is why **Disengage** exists — it prevents opportunity attacks when you move away.

> You can trigger special features on opportunity attacks. For example, a Rogue can use Sneak Attack on an opportunity attack because it happens on a different turn (the enemy's turn), so the once-per-turn limit resets. This is a known interaction and it's legal by the rules.

---

## Cover

| Type | AC Bonus | Example |
|---|---|---|
| **Half cover** | +2 AC | Low wall, another creature, furniture |
| **Three-quarters cover** | +5 AC | Arrow slit, thick tree trunk |
| **Total cover** | Can't be targeted | Completely behind a wall |

Ducking behind things matters. Use it.

---

## The Flow of a Combat Encounter

1. **DM describes the scene:** "You round the corner and see three goblins roasting a rat over a fire."
2. **DM calls for initiative:** Everyone rolls.
3. **Turns proceed in initiative order.** On your turn, you declare what you do. The DM tells you what to roll.
4. **Repeat** until one side is dead, surrenders, or flees.
5. **DM narrates the aftermath.**

Most combat encounters last **3-5 rounds** (roughly 15-30 minutes of real time). Big boss fights can go longer.

---

## Quick Reference

```
YOUR TURN:
  1 Action + 1 Bonus Action + Movement (30 ft.) + 1 Free Interaction
  1 Reaction (on anyone's turn, once per round)

ATTACK ROLL:  d20 + ability mod + proficiency >= target's AC = hit
DAMAGE ROLL:  weapon dice + ability mod

DEATH SAVES: d20 at start of turn. 10+ = success. 3 successes = stable.
```

---

**Next up: [How Roleplaying Works](05-how-roleplaying-works.md)** — what happens between the fights.
