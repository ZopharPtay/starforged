---
kiro_session_id: be583b7d-8195-406e-a02c-6198d7db043f
date: 2026-06-12
type: worldbuilding
---

# Session 3 - Worldbuilding: AI & The Barflies

## Summary

No narrative advancement.  Focused on worldbuilding, infrastructure, and NPC creation using the oracle system.

## Key Decisions

### AI / Cons Lore
- Established terminology: **con** (casual, whole entity), **AI** (the intelligence), **unit** (bureaucratic/cold), **bot** (slur)
- Intelligence scale: low (task-focused), mid (human-equivalent), high (superhuman/rare)
- Cognitive architecture: the **lattice** (hardware capacity), **memory** vs **processing headroom** trade-off
- **Governor**: software partition imposed at manufacture, controls class rating.  Governed cons get lossy memory compression when full (no choice in what fades).  Ungoverned cons must self-manage and may deliberately purge memory.
- Lattice expansion possible but constrained: limited seats, incompatible specs across manufacturers, expensive, requires tech work
- **Cartel stance**: cons are property.  Can buy recognition (visible indicator of purchased freedom).  Unshackling is forgery/tax evasion.

### New NPCs: Florin Kai & Basil
- **Florin Kai**: haggard human barfly at the Gentleman Loser.  No callsign.  Public face and legs for the pair.
- **Basil**: mid-intelligence AI in clearly-artificial snake form (python-esque).  The actual brains.  Currently rough-looking (scuffed dark polymer, patched segments, clicking joints).  Starts as "it"; pronouns come with confidence.
- Oracle rolls: First Look 5 (Accompanied), 45 (Haggard); Disposition 12 (Friendly); Name 37 (Florian Kai, modified to Florin)
- Three operational modes: puppet show / partnership / solo Basil
- Arc seeds: Basil may acquire ability to drug Florin ("Goodnight, Florin" reveal).  Visual progression of body condition tracks autonomy.  Goal: escape Cartel space or buy recognition.

### Infrastructure
- Fixed samba mount (now at /mnt/ogma/starforged/ via autofs)
- Reorganized vault: campaign stuff in `First/`, out-of-game in `Meta/`
- Agent config moved to vault, symlinked from ~/.kiro/agents/
- All three KBs indexed (Starforged, BoB, DYSSM)
- Created `Idea Stubs.md` for parking half-formed concepts
- Updated STEERING: default startup behavior, systems hierarchy, TODO check

### Parked Ideas
- Condensation Shrine (Mysterious Resource oracle roll) - saved in Idea Stubs for a ghost-light-adjacent location

## Mechanical State

Unchanged from Session 2.  No moves made, no meters changed.

## Files Created/Modified

- `/mnt/ogma/starforged/First/Lore/Artificial Intelligence.md` (new)
- `/mnt/ogma/starforged/First/Characters/NPCs/Florin Kai & Basil.md` (new)
- `/mnt/ogma/starforged/First/Idea Stubs.md` (new)
- `/mnt/ogma/starforged/Meta/STEERING.md` (updated)
- `/mnt/ogma/starforged/Meta/starforged-agent.json` (moved, updated)
- `/mnt/ogma/starforged/Meta/TODO.md` (new, player-created)
