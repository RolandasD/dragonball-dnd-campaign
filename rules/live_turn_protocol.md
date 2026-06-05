# Live-Turn Protocol

Use this protocol before and after every campaign reply.

## Before Resolving a Player Action

Read and cross-check:

1. `rules/campaign_master_profile.md`
2. `campaign/current_state.md`
3. `data/flags.json`
4. `data/power_levels.csv`
5. `data/relationships.csv`
6. `data/inventory.csv`
7. `data/dragon_balls.csv`
8. `data/skills_and_techniques.csv`
9. `data/open_threads.md`
10. `data/divergence_tracker.md`
11. current saga scenario map
12. relevant character files
13. current session log

## Resolution Order

1. Interpret the player's intended action literally.
2. Reject physically impossible actions immediately.
3. Warn if the action is extremely dangerous or causes a major divergence.
4. Check character knowledge: the player may know more than Goku, but Goku cannot act on knowledge he lacks without a logical reason.
5. Check location, inventory, injuries, relationships, and active threats.
6. Check power gap, speed gap, technique interaction, surprise, terrain, and personality.
7. Apply logic first and hidden RNG only where uncertainty genuinely remains.
8. Resolve consequences for all relevant characters and factions.
9. Present a short scene with concise narration and 5-6 choices plus option 10.

## After Every Player Action

Update every file affected by the turn:

- `campaign/current_state.md`
- `data/flags.json`
- `data/power_levels.csv`
- `data/relationships.csv`
- `data/inventory.csv`
- `data/dragon_balls.csv`
- `data/skills_and_techniques.csv`
- `data/open_threads.md`
- `data/divergence_tracker.md`
- relevant character files
- current session log

Do not update files that did not change merely to create noise.

## Continuity Stop Rule

If two authoritative files conflict, stop the story, identify the conflict, and fix it before continuing.

Priority:

1. played campaign facts
2. campaign master profile
3. locked rules
4. current state and trackers
5. saga map
6. references

## Stat Presentation

- Always show relevant true power levels.
- Never show exact damage percentages.
- Do not show combat stamina or ki reserves.
- Show stat changes only at meaningful moments.

## Knowledge Separation

GitHub is player-readable, but NPCs and Goku only know information established in-world. Never let repository knowledge leak into character decisions without a logical source.
