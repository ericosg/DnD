# D&D 5e Character Creation — AI-Assisted Prompt Template

Use this prompt template with an AI assistant (Claude, ChatGPT, etc.) to recreate the learning journey that built this repository. By the end, you'll have a personalized tutorial, a complete character sheet, a backstory, and a cheat sheet — all tailored to your character.

---

## How to Use This

1. Copy the **starter prompt** below into your AI assistant
2. Follow the conversation flow — the AI will teach you the basics and help you make decisions
3. At each **decision point**, make your choice before moving on
4. Save the outputs as markdown files as you go

You don't need to follow this rigidly. Skip sections you already know. Linger on parts that interest you. The goal is to arrive at a character you're excited to play.

---

## Starter Prompt

Copy and paste this to begin:

```
I want to learn D&D 5th Edition from scratch and build my first character.
Please guide me through the entire process step by step, creating markdown
documents as we go. I want to end up with:

1. A tutorial that teaches me the core rules
2. A complete character with a filled-out character sheet
3. A backstory for my character
4. A cheat sheet I can bring to the table

Here's what I know:
- [Describe your experience: video games, board games, other RPGs, or nothing]
- [Describe your campaign info: what edition, what level, any restrictions]
- [Describe any character ideas you have, even vague ones]

Start with the basics — what is D&D, how does it work — and we'll build
from there. Ask me questions when you need my input for decisions.
```

---

## The Learning Path

The conversation should naturally flow through these phases. Use the checkboxes to track your progress.

### Phase 1: Learn the Fundamentals

- [ ] **What is D&D?** — How it differs from video/board games, the role of the DM, the core d20 mechanic, dice notation
- [ ] **Ability Scores & Skills** — The six stats (STR, DEX, CON, INT, WIS, CHA), modifiers, proficiency bonus, advantage/disadvantage
- [ ] **Races & Classes** — Overview of all options, what each class does, complexity ratings

**Decision point:** Start thinking about what kind of character excites you. Warrior? Spellcaster? Sneaky? Supportive? Don't commit yet — just explore.

### Phase 2: Shape Your Character Concept

- [ ] **Pick a class direction** — Based on what excites you, narrow down to 1-2 classes
- [ ] **Pick a race** — Consider what fits your concept mechanically and narratively
- [ ] **Explore the setting** — Ask about the world your DM is running. What factions, cultures, or regions fit your character?
- [ ] **Develop a concept** — Who is this person? What's their vibe? What's their story?

**Decision point:** Lock in your race and class. You can still adjust details, but the core identity is set.

**Prompt to continue:**
```
I want to play a [race] [class]. My character concept is [describe the vibe,
even vaguely — e.g., "a quiet, disciplined warrior" or "a charismatic
trickster" or "a scholar who stumbled into adventure"].

Help me flesh this out. What are my mechanical options (subclass, stats,
feat if applicable)? And what kind of backstory fits this concept in
[setting name]?
```

### Phase 3: Build the Character Mechanically

- [ ] **Ability scores** — Choose a method (Standard Array, Point Buy, or Rolling) and assign scores
- [ ] **Stat priority** — Optimize for your class's primary stat, then decide on secondary stats
- [ ] **Feat selection** (if applicable — Variant Human or level 4+) — Review all feats, pick one that fits your concept
- [ ] **Background** — Review all backgrounds, pick one that gives useful skills and fits your story
- [ ] **Skill proficiencies** — Allocate all skill picks from class, background, and race
- [ ] **Equipment** — Choose starting gear or buy with gold

**Prompt for reference docs:**
```
Before I pick my [feat/background/skills/equipment], can you create a
complete reference document listing ALL options with descriptions? I want
to study them and make an informed choice.
```

**Decision point:** All mechanical choices are final. Your character is playable.

### Phase 4: Write the Backstory

- [ ] **Establish the basics** — Where are you from? What did you do before adventuring? Why are you adventuring now?
- [ ] **Connect to the setting** — Ground your backstory in the world's lore, factions, and geography
- [ ] **Create hooks for the DM** — Leave open threads the DM can pull on
- [ ] **Separate player knowledge from DM knowledge** — What does the party see? What does only the DM know?
- [ ] **Pick a name** — Something that fits the culture and carries meaning

**Prompt to continue:**
```
Let's write my backstory. Here's what I have in mind:
- [Origin/background idea]
- [Motivation for adventuring]
- [Any secrets or hidden agendas]
- [Personality traits — how they act, what they value, what they fear]

Write it as a narrative I can give to my DM, with a separate section of
DM-only notes that includes what's fixed, what's open for the DM to
define, and story hooks they can use.
```

### Phase 5: Compile Final Documents

- [ ] **Character sheet** — All stats, skills, equipment, features, attacks, and combat turn templates in one document
- [ ] **Backstory** — The narrative + DM notes, finalized
- [ ] **Cheat sheet** — A print-ready reference tailored to your class with the universal rules

**Prompt to compile:**
```
Let's compile everything into final documents:

1. A complete character sheet with all stats, skills, attacks, equipment,
   features, and a combat quick-reference section
2. My finalized backstory with DM notes
3. A cheat sheet tailored to my class that I can print and bring to the table

Include a "what to bring to session" checklist at the end of the character sheet.
```

---

## Optional: Hosting Guide

If you're hosting the game at your place:

```
I'm hosting D&D at my home. What kind of table and seating works best?
What do I need to provide vs. what does the DM bring? Any hosting tips
for food, breaks, lighting, etc.?
```

---

## Tips for the Best Results

### Give the AI context
The more it knows about your experience level, your DM's rules, and your preferences, the better it can tailor everything. Don't be afraid to say "I don't know" — that's useful information.

### Make decisions, don't defer
The AI can present options and recommendations, but the creative decisions should be yours. "What do you think?" gives you a generic answer. "I want to be a fire mage who's afraid of the dark" gives you a character.

### Ask "why" and "what if"
- "Why is DEX important for a Rogue?"
- "What if I put WIS as my second stat instead of CON?"
- "What would happen if my character refused this mission?"

These questions produce the most useful explanations.

### Request reference documents
Before making big choices (class, feat, background, skills), ask for a complete reference listing ALL options. Studying the full list helps you make informed decisions and often reveals options you didn't know existed.

### Don't optimize — personalize
The "best" character isn't the one with the highest damage output. It's the one you're most excited to play. If a suboptimal choice makes your character more interesting, take it. The table will remember your cool backstory long after they've forgotten your DPS.

### Share your results
If you build a character using this process, consider adding it to the `example-build/` folder in this repository as a pull request. Seeing different character concepts helps other new players understand what's possible.

---

## File Checklist

By the end of this process, you should have:

```
your-character/
├── character-sheet.md    — Complete mechanical character sheet
├── backstory.md          — Narrative backstory + DM notes
└── cheat-sheet.md        — Print-ready session reference
```

Optional extras you may have generated along the way:
```
├── reference-feats.md        — All feats with notes
├── reference-backgrounds.md  — All backgrounds with notes
├── reference-skills.md       — All skills explained
└── reference-equipment.md    — Weapons, armor, gear, costs
```

---

*This template was built from an actual first-timer's learning session using [Claude Code](https://claude.com/claude-code). The [example build](example-build/) in this repository is the character that came out of it.*
