# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

A free, practical guide for learning D&D 5th Edition from scratch. Built for players coming from video games (Baldur's Gate 3) and board games (HeroQuest), but useful for any first-timer.

This is a companion repository to [DnDnAi](https://github.com/ericosg/DnDnAi), an AI-powered D&D Discord bot. The guides here informed the bot's rules engine, character sheet format, and DM system prompt. The character sheet markdown format used in `example-build/character-sheet.md` is the format the bot's parser expects from players.

## Repository Structure

```
guides/           Numbered tutorial sequence (read in order)
reference/        Detailed lookup docs for character creation
example-build/    Complete worked character (Fūsetsu, ninja rogue)
prompt.md         AI-assisted character creation template
```

### Tutorial Sequence (`guides/00–07`)
- `00` — Hosting & setup (table, supplies, logistics)
- `01` — What D&D is (framed for video game / board game players)
- `02` — Ability scores, modifiers, skills, proficiency, advantage/disadvantage
- `03` — Races & classes (all core options with complexity ratings)
- `04` — Combat (initiative, action economy, attacks, death saves, conditions)
- `05` — Roleplaying (IC/OOC, social skills, party dynamics)
- `06` — Etiquette & table tips (unwritten rules)
- `07` — Cheat sheet (print-ready session reference)

### Reference Library (`reference/`)
- `backgrounds.md` — all 5e backgrounds with skills, features, fitness analysis
- `equipment.md` — weapons, armor, adventuring gear, costs
- `feats.md` — complete feat catalog with class recommendations
- `skills.md` — all 18 skills with practical examples

### Example Build (`example-build/`)
- `README.md` — character concept (Kara-Tur lore, Silent Cord order, mechanical mapping)
- `character-sheet.md` — complete level 1 sheet (Variant Human Rogue/Assassin)
- `backstory.md` — in-character narrative + DM notes with plot hooks

### Prompt Template (`prompt.md`)
Step-by-step AI-assisted character creation walkthrough. Five phases from fundamentals through final document compilation.

## Writing Conventions

- Guides are written in approachable, direct tone — no condescension, assumes smart-but-new reader
- Video game analogies (especially BG3) are used throughout to bridge knowledge gaps
- Mechanical details are always paired with practical "when would I use this" examples
- The example build (Fūsetsu) appears throughout guides for concrete illustrations
- Each guide is self-contained but references others via relative links
- Reference docs include fitness analysis for the example build

When editing or creating new content:
- Maintain the numbered guide sequence (next would be `08`)
- Use relative markdown links between documents
- Include example build references where relevant
- Keep the cheat sheet (`07`) updated with any new mechanics

## Connection to DnDnAi

The character sheet format in `example-build/character-sheet.md` uses `**Key:** Value` pairs and `## Section` headings with bullet lists. This exact format is what the DnDnAi bot's character sheet parser (`game/characters.ts`) expects. If you change the format here, the parser may need updating there.
