# Campaign Readiness Audit

## Verdict

The campaign is structurally ready to play, with one unresolved policy decision: how to store genuinely hidden simulation values during active play while keeping all GitHub files player-readable.

## Fixed During Audit

- Replaced placeholder `data/power_levels.csv` values.
- Removed duplicate `data/opening_stats.csv`.
- Updated README workflow and final campaign settings.
- Updated source policy to exclude original Dragon Ball theatrical retellings, Heroes, Xenoverse, and game-original arcs by default.
- Updated master chronology to reflect GT as expected unless impossible and to align movie inclusion rules.
- Added strict live-turn protocol.
- Added inventory tracker.
- Added Dragon Ball location tracker.
- Added skills and techniques tracker.
- Added open plot thread tracker.
- Added tracker scales.
- Added live Goku character file.
- Added Session 001 log.

## Confirmed Ready

- Current saga scenario map exists.
- Current state is initialized.
- Flags are initialized.
- Power levels are initialized.
- Relationships are initialized.
- Inventory is initialized.
- Dragon Ball locations are initialized.
- Skills and techniques are initialized.
- Divergence tracking exists.
- Open plot threads exist.
- Source priority is defined.
- Turn-resolution protocol is defined.
- Session logging exists.
- No remaining TBD placeholders found.

## Remaining Decision

The campaign requires a policy for hidden stats and hidden NPC motives.

Current choices conflict:

- no hidden DM files in GitHub
- player can read all GitHub files at any time
- hidden systems should remain hidden during active play
- full hidden-stat reveal after each saga

Choose one:

A. Store hidden values openly in GitHub; player agrees not to inspect them during active play.
B. Use a separate hidden branch/file set; player does not read it until saga reveal.
C. Do not store hidden numeric values; use qualitative hidden simulation notes and reconstruct saga-end reveals from events.
D. Keep hidden values outside GitHub in the active chat/session only, accepting some continuity risk.

## Recommended Choice

B is the most reliable for continuity. C is the cleanest if complete player-readability is more important than exact hidden-number simulation.
