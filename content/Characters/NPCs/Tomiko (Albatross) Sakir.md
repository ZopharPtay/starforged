# Tomiko "Albatross" Sakir

**Role:** Researcher
**Pronouns:** TBD
**Callsign:** Albatross
**Faction:** TBD (decide before play)
**Status:** Alive
**Connection Rank:** TBD

## Oracle Results

- First Look: Energetic
- Initial Disposition: Desperate
- Character Role: Researcher
- Character Goal: Secure a resource
- Revealed Character Aspect: Driven

## Summary

Energetic, desperate, driven.  A researcher who needs something retrieved from a derelict and can't do it themselves.  Hires [[Characters/Leight/Leight|Leight]] as a courier/retrieval specialist.

## The Job

Retrieve a macguffin from a derelict starship.  Details TBD:
- What is the item?  (Ties to "Secure a resource" goal)
- Which faction does Albatross belong to or work for?
- Why can't they go themselves?

This is a courier run: Swear an Iron Vow to transport and protect something precious.  The Courier asset kicks in once the item is in hand and needs delivering back.

## The Derelict

- **Location:** Deep space (within the Marigny; sublight-reachable from Paxton, but a long haul)
- **Type:** Starship
- **Condition:** Damaged or breached
- **Outer First Look:** Stripped exterior
- **Inner First Look:** Littered with corpses
- **Theme:** Infested

### Access

- **Area:** Corridor
- **Feature:** Blood trail
- **Peril:** Alarm or failsafe is triggered
- **Opportunity:** Encounter with a friendly survivor, explorer, or denizen

### Infestation

- **Feature:** Evidence of an ill-fated victim
- **Peril:** Creatures reveal new aspects or abilities
- **Opportunity:** Early warning of an attack or ambush

### The Creatures

- **Environment:** Land
- **Basic Form:** Beast / mammal
- **Scale:** Small (dog-sized)
- **First Look:** Mineral or metallic
- **Behavior:** Forager

## The Survivor: Ayako "Scout" Becker

Found inside the derelict (the "friendly survivor" from the Access opportunity roll).  Not original crew; most likely the remnant of an unlicensed salvage team that went in quiet and got trapped.  Nobody is looking for them because nobody knows they were there.

- **Given Name:** Ayako
- **Callsign:** Scout
- **Family Name:** Becker
- **First Look:** Distracted
- **Initial Disposition:** Desperate
- **Role:** Soldier
- **Goal:** Cure an ill
- **Revealed Aspect:** Loving

A desperate soldier-turned-salvager trapped aboard, trying to cure something (themselves?  a crewmate who didn't make it?  something contracted from the infestation?).  Distracted by that goal, but not hostile.  Could be an ally inside the wreck or a complication if their needs conflict with Leight's objective.  No rescue is coming because nobody knows they were there.

## Open Questions

- How does Leight hear about this job?  (Flint?  Job board?  Albatross approaches directly?)
- What's the macguffin?  Research data?  A physical specimen?  A piece of precursor tech?
- Is the derelict known to be infested, or is that a surprise?
- Does the job pay cash, or is Albatross offering something else (e-drive parts?  a connection?  information?)

## Public Knowledge & Rumour Seeds

Derelicts are common in the Forge; finding one isn't news.  But this one has a reputation:

- A stripped hulk detected drifting in deep space within the Marigny.  Coordinates known to salvage crews.
- Early teams hit the exterior (hence "stripped"), but pulled out fast from the interior.  Rumours about why: bad air, something moving in the dark, a team member who stopped responding on comms.
- Flagged informally as "not worth the risk" by local salvage operators.  No official interdiction; just nobody wants the job.
- Albatross can't find a taker because experienced crews know better.  Leight gets the offer because he's cheap, desperate, and new enough not to have heard the stories.

**Possible seed lines for earlier journals:**
- A job board posting: "RETRIEVAL - DEEP SPACE - HAZARD RATE.  Contact T. Sakir, berth 14."
- Overheard at the Gentleman Loser: "...pulled out after one shift.  Said the walls were scratching back."
- Flint mentions a crew that came through needing hull patches after a salvage run gone wrong; wouldn't say where they'd been.

## Raw Oracle Data

```iron-vault-mechanics
oracle-group name="NPC: [[Tomiko “Albatross” Sakir]]" {
    oracle name="[Character Oracles \/ Character Name \/ Given Name](datasworn:oracle_rollable:starforged\/character\/name\/given_name)" result="Tomiko" roll=89
    oracle name="[Character Oracles \/ Character Name \/ Callsign](datasworn:oracle_rollable:starforged\/character\/name\/callsign)" result="Albatross" roll=1
    oracle name="[Character Oracles \/ Character Name \/ Family Name](datasworn:oracle_rollable:starforged\/character\/name\/family_name)" result="Sakir" roll=26
    oracle name="[Character Oracles \/ First Look](datasworn:oracle_rollable:starforged\/character\/first_look)" result="Energetic" roll=34
    oracle name="[Character Oracles \/ Initial Disposition](datasworn:oracle_rollable:starforged\/character\/initial_disposition)" result="Desperate" roll=65
    oracle name="[Character Oracles \/ Character Role](datasworn:oracle_rollable:starforged\/character\/role)" result="Researcher" roll=73
    oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Secure a resource" roll=68
    oracle name="[Character Oracles \/ Revealed Character Aspect](datasworn:oracle_rollable:starforged\/character\/revealed_aspect)" result="Driven" roll=34
}
oracle-group name="Derelict Oracles: New Derelict Oracles" {
    oracle name="[Derelict Oracles \/ Location](datasworn:oracle_rollable:starforged\/derelict\/location)" result="Deep Space" roll=94
    oracle name="[Derelict Oracles \/ Condition](datasworn:oracle_rollable:starforged\/derelict\/condition)" result="Damaged or breached" roll=71
    oracle name="[Derelict Oracles \/ Outer First Look](datasworn:oracle_rollable:starforged\/derelict\/outer_first_look)" result="Stripped exterior" roll=88
    oracle name="[Derelict Oracles \/ Inner First Look](datasworn:oracle_rollable:starforged\/derelict\/inner_first_look)" result="Littered with corpses" roll=58
}
oracle name="[Derelict Oracles \/ Derelict Type (by location) \/ Deep Space](datasworn:oracle_rollable:starforged\/derelict\/type\/deep_space)" result="Starship" roll=10
oracle-group name="Derelict Oracles > Access: New Derelict Oracles > Access" {
    oracle name="[Derelict Oracles \/ Access \/ Area](datasworn:oracle_rollable:starforged\/derelict\/access\/area)" result="Corridor" roll=15
    oracle name="[Derelict Oracles \/ Access \/ Feature](datasworn:oracle_rollable:starforged\/derelict\/access\/feature)" result="Blood trail" roll=9
    oracle name="[Derelict Oracles \/ Access \/ Peril](datasworn:oracle_rollable:starforged\/derelict\/access\/peril)" result="Alarm or failsafe is triggered" roll=1
    oracle name="[Derelict Oracles \/ Access \/ Opportunity](datasworn:oracle_rollable:starforged\/derelict\/access\/opportunity)" result="Encounter with a friendly survivor, explorer, or denizen" roll=35
}
oracle-group name="NPC: Ayako “Scout” Becker" {
    oracle name="[Character Oracles \/ Character Name \/ Given Name](datasworn:oracle_rollable:starforged\/character\/name\/given_name)" result="Ayako" roll=14
    oracle name="[Character Oracles \/ Character Name \/ Callsign](datasworn:oracle_rollable:starforged\/character\/name\/callsign)" result="Scout" roll=74
    oracle name="[Character Oracles \/ Character Name \/ Family Name](datasworn:oracle_rollable:starforged\/character\/name\/family_name)" result="Becker" roll=74
    oracle name="[Character Oracles \/ First Look](datasworn:oracle_rollable:starforged\/character\/first_look)" result="Distracted" roll=28
    oracle name="[Character Oracles \/ Initial Disposition](datasworn:oracle_rollable:starforged\/character\/initial_disposition)" result="Desperate" roll=68
    oracle name="[Character Oracles \/ Character Role](datasworn:oracle_rollable:starforged\/character\/role)" result="Soldier" roll=86
    oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Cure an ill" roll=15
    oracle name="[Character Oracles \/ Revealed Character Aspect](datasworn:oracle_rollable:starforged\/character\/revealed_aspect)" result="Loving" roll=61
}
oracle name="[Location Theme Oracles \/ Theme Type](datasworn:oracle_rollable:starforged\/location_theme\/type)" result="[Infested](datasworn:oracle_collection:starforged\/location_theme\/infested)" roll=39
oracle-group name="Location Theme Oracles > Infested: New Location Theme Oracles > Infested" {
    oracle name="[Location Theme Oracles \/ Infested \/ Feature](datasworn:oracle_rollable:starforged\/location_theme\/infested\/feature)" result="Evidence of an ill-fated victim" roll=33
    oracle name="[Location Theme Oracles \/ Infested \/ Peril](datasworn:oracle_rollable:starforged\/location_theme\/infested\/peril)" result="Creatures reveal new aspects or abilities" roll=27
    oracle name="[Location Theme Oracles \/ Infested \/ Opportunity](datasworn:oracle_rollable:starforged\/location_theme\/infested\/opportunity)" result="Early warning of an attack or ambush" roll=44
}
oracle-group name="Creature: New Creature" {
    oracle name="[Creature Oracles \/ Environment](datasworn:oracle_rollable:starforged\/creature\/environment)" result="Land" roll=39
    oracle name="[Basic form](datasworn:oracle_rollable:starforged\/creature\/basic_form\/land)" result="Beast \/ mammal" roll=17
    oracle name="[Creature Oracles \/ Scale](datasworn:oracle_rollable:starforged\/creature\/scale)" result="Small (dog-sized)" roll=25
    oracle name="[Creature Oracles \/ Creature First Look](datasworn:oracle_rollable:starforged\/creature\/first_look)" result="Mineral or metallic" roll=72
    oracle name="[Creature Oracles \/ Encountered Behavior](datasworn:oracle_rollable:starforged\/creature\/encountered_behavior)" result="Forager" roll=20
}

```
