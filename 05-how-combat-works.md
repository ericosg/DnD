# How Combat Works — The Turn-by-Turn Breakdown

You know this from BG3. Tabletop combat is the same system, just without the computer doing the math for you.

---

## Starting Combat: Initiative

When a fight breaks out, everyone rolls **initiative** to determine turn order.

**Initiative = d20 + DEX modifier**

> With your build: if you take the **Alert** feat, you add +5 on top of that. With high DEX + Alert, you'll almost always go first. A ninja striking before anyone reacts.

The DM rolls initiative for all enemies. Everyone's rolls are ranked from highest to lowest — that's the turn order for the entire fight. It doesn't change unless a special ability modifies it.

---

## Your Turn: The Action Economy

On each of your turns, you get:

| Resource | What It Is | Examples |
|---|---|---|
| **1 Action** | Your main thing | Attack, Dash, Dodge, Hide, Use an Object, Cast a Spell |
| **1 Bonus Action** | A smaller thing (only if an ability grants one) | Off-hand attack (dual wielding), Cunning Action (Rogue), some spells |
| **Movement** | Move up to your speed (usually 30 ft.) | Walk, climb, swim. You can split movement before and after your action. |
| **1 Free Interaction** | A tiny thing | Open a door, draw a weapon, shout a warning |
| **1 Reaction** | A response on someone else's turn (once per round) | Opportunity attack, the Shield spell, Uncanny Dodge (Rogue feature) |

### How This Looks for Your Ninja Rogue

A typical combat turn for you:

1. **Move** 15 ft. to flank the enemy.
2. **Action:** Attack with your main-hand shortsword. Roll d20 + DEX + proficiency. If you hit and have advantage (or an ally is adjacent to the target), add **Sneak Attack** damage.
3. **Bonus Action:** Attack with your off-hand shortsword (dual wield). If your first attack missed, this is your second chance to land Sneak Attack.
4. **After your turn:** If an enemy moves away from you, you can use your **Reaction** for an opportunity attack.

Or alternatively:

1. **Action:** Attack with main-hand.
2. **Bonus Action: Cunning Action — Hide.** Instead of the off-hand attack, you duck behind cover. Now you're hidden. On your next turn, you attack from hiding = advantage = guaranteed Sneak Attack setup.

This is the core tactical decision for dual-wield Rogues: **off-hand attack for a second chance to Sneak Attack, or Cunning Action for positioning/setup?**

---

## Making an Attack Roll

1. Roll **d20**
2. Add your **ability modifier** (DEX for finesse weapons)
3. Add your **proficiency bonus** (you're proficient with shortswords)
4. Compare to the target's **AC (Armor Class)**
5. **Meet or beat AC = hit. Under = miss.**

> Example at level 1: d20 + 3 (DEX) + 2 (proficiency) = d20 + 5.
> Against an enemy with 15 AC, you need to roll a 10 or higher. That's a 55% chance.

### Critical Hits and Misses

- **Natural 20** (the die shows 20): Automatic hit, **double all damage dice** (not modifiers). Devastating with Sneak Attack — all those Sneak Attack dice get doubled too.
- **Natural 1** (the die shows 1): Automatic miss, regardless of modifiers. Some DMs add comedic fumble effects, but by RAW (Rules As Written) it's just a miss.

---

## Damage

When you hit, you roll damage:

**Main-hand shortsword:** 1d6 + DEX modifier
**Off-hand shortsword:** 1d6 only (you don't add your DEX modifier to off-hand damage unless you have a special feature)
**Sneak Attack (level 1):** +1d6 (once per turn, scales with level)

> First-round Assassin example at level 3: You surprise an enemy. Auto-crit.
> Main-hand: 2d6 (doubled crit) + DEX modifier + Sneak Attack 4d6 (2d6 doubled) = potentially 6d6 + 3. That's an average of **24 damage** in one hit at level 3. Some enemies just drop.

---

## Dual Wielding Rules

Since this is core to your build, here are the specifics:

1. When you take the **Attack action** with a **light melee weapon** in one hand, you can use your **bonus action** to attack with a different **light** weapon in the other hand.
2. Both weapons must have the **light** property. Shortswords, scimitars, daggers, and handaxes all qualify.
3. You **don't add your ability modifier to the off-hand damage** (unless you take the Two-Weapon Fighting style, which Rogues don't normally get).
4. You can draw both weapons on the same turn using your free interaction (some DMs are strict about this — technically drawing two weapons requires two interactions. Ask your DM).

**Why dual wield as a Rogue?**
Not for raw damage — the off-hand hit without a modifier is weak. It's for **reliability**. You get Sneak Attack only once per turn, but if you miss your first attack, the off-hand gives you a second chance. It's insurance.

---

## Conditions You'll See Often

| Condition | Effect | How You Get It |
|---|---|---|
| **Prone** | Disadvantage on attacks. Melee attacks against you have advantage, ranged have disadvantage. | Knocked down, tripped |
| **Restrained** | Speed 0, disadvantage on attacks, attacks against you have advantage | Nets, grapples, web spell |
| **Poisoned** | Disadvantage on attack rolls and ability checks | Poison, some monster abilities |
| **Frightened** | Disadvantage on checks/attacks while you can see the source, can't move closer to it | Dragon fear, spells |
| **Incapacitated** | Can't take actions or reactions | Some spells, being stunned |
| **Stunned** | Incapacitated + can't move + auto-fail STR/DEX saves + attacks against you have advantage | Monk's Stunning Strike, some spells |
| **Unconscious** | Out cold. Auto-fail STR/DEX saves, attacks have advantage, melee hits are auto-crits | Dropping to 0 HP, sleep spell |

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

> **As a Rogue:** You're not tanky. You will go down sometimes. This is fine — it's part of the game. Play smart: use Cunning Action to Disengage or Hide when things get dangerous. Don't stand in the open trading blows with a knight. Strike, then vanish.

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

**Rogue advantage:** Cunning Action (level 2) lets you **Dash, Disengage, or Hide** as a **bonus action** instead of your action. This is game-changing. It means you can:
- Attack AND hide in the same turn
- Attack AND disengage safely
- Dash AND dash (bonus + action) to cover enormous ground

---

## Opportunity Attacks

When a creature **moves out of your melee reach** (5 ft. for most weapons), you can use your **reaction** to make one melee attack against them. This is free — it doesn't cost your action.

This is why **Disengage** exists — it prevents opportunity attacks when you move away.

As a Rogue with Cunning Action, you can Disengage as a bonus action, which means you can freely dance in and out of combat without getting punished. Very ninja.

> **Yes, you can Sneak Attack on an opportunity attack.** It's a separate turn (the enemy's turn), so your once-per-turn Sneak Attack refreshes. This is a known interaction and it's legal. Don't feel bad about it.

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

ATTACK ROLL:  d20 + ability mod + proficiency ≥ target's AC = hit
DAMAGE ROLL:  weapon dice + ability mod (no mod on off-hand)

ROGUE SNEAK ATTACK: once per turn, when you have advantage OR
                     an ally is within 5 ft. of the target

CUNNING ACTION (bonus action): Dash, Disengage, or Hide

DEATH SAVES: d20 at start of turn. 10+ = success. 3 successes = stable.
```

---

**Next up: How Roleplaying Works** — what happens between the fights.
