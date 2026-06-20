---
name: Nassir Okoro
xp_spent: 0
xp_added: 0
momentum: 4
edge: 2
heart: 1
iron: 1
shadow: 3
wits: 2
health: 5
spirit: 5
supply: 5
Quests_Progress: 0
Quests_XPEarned: 0
Bonds_Progress: 0
Bonds_XPEarned: 0
Discoveries_Progress: 0
Discoveries_XPEarned: 0
iron-vault-kind: character
assets:
  - id: asset:starforged/path/courier
    abilities:
      - true
      - false
      - false
    controls:
      safety: 0
    options: {}
  - id: asset:starforged/path/shade
    abilities:
      - true
      - false
      - false
    controls: {}
    options: {}
  - id: asset:starforged/command_vehicle/starship
    abilities:
      - true
      - false
      - false
    controls:
      integrity: 5
      integrity/battered: false
      integrity/cursed: false
    options:
      name: The Hulking Anguish
  - id: asset:starforged/module/vehicle_bay
    abilities:
      - true
      - false
      - false
    controls:
      broken: false
    options: {}
cursed: false
callsign: Leight
pronouns: He/Him
description: |2-
    Look: Unremarkable by design.  Average height, average build, the kind of face that doesn't stick in memory.  Dresses to blend: working-class spacer clothes, nothing flashy, nothing ragged.
    
    Act: Quiet, observant, economy of motion.  Doesn't fill silences.  Keeps his hands busy when he's thinking.  Trusts objects more than people.
    
    Wear: Practical courier gear.  Jacket with too many pockets.  Nothing that draws the eye.
    
    Background: Former Cartel operative who worked off his debts as a courier and smuggler.  A friend died to buy his freedom on his last job.  Now free, broke, alone in a beat-up freighter with one tank of gas and a gift for making things disappear.
    
    Gift: Not personal invisibility.  He makes things unnoticeable: a crate, a data chip, a modification.  Eyes slide past what he hides.
    
    Callsign origin: Tried to go by "Sleight" (as in sleight of hand).  Everyone misheard it as "Light."  He gave up correcting them but refuses to spell it the boring way.  It's Leight.
---
```iron-vault-mechanics
track name="[[First\/Progress\/Flint.md|Flint]]" status="added"
```



```iron-vault-character-info
```

```iron-vault-character-stats
```

```iron-vault-character-meters
```

```iron-vault-character-special-tracks
```

```iron-vault-character-impacts
```

```iron-vault-character-assets
```

## Backstory
```iron-vault-mechanics
oracle name="[Campaign Launch Oracles \/ Backstory Prompts](datasworn:oracle_rollable:starforged\/campaign_launch\/backstory_prompts)" result="Your ambitions outgrew your humble origins" roll=93
```

Solo-style beginnings, but instead of going to Imperial Academy he took on - and worked off -debts to [[The Cartel]], more along the lines of Qi'ra's arc?  Now free of both the debts and the protections of [[The Cartel]], he is adrift in [[First/Characters/The Hulking Anguish/The Hulking Anguish|The Hulking Anguish]], an old beat-up freighter that he owns outright with just enough money for one more tank of gas. 


## Background Vows

```iron-vault-mechanics
track name="[[First\/Progress\/The Secret (Background Vow).md|I vow to protect a secret]]" status="added"
track name="[[First\/Progress\/Repair a Technology (Background Vow).md|Repair a Technology (Background Vow)]]" status="added"
track name="[[First\/Progress\/Pay A Debt (Background Vow).md|Pay A Debt]]" status="added"


```

 > [!note] Rolled 5 vows which seemed excessive.  Trimmed to 3: Protect the Secret, Pay a Debt, Repair a Technology.  Defeat a Rival and Deflect a Tool were dropped during session 0.
```iron-vault-mechanics
oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Roll twice" roll=94 {
    oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Protect a secret" roll=51
    oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Roll twice" roll=93 {
        oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Roll twice" roll=98 {
            oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Repair a technology" roll=58
            oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Roll twice" roll=91 {
                oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="[Action](datasworn:oracle_rollable:starforged\/core\/action) + [Theme](datasworn:oracle_rollable:starforged\/core\/theme)" roll=86 {
                    oracle name="[Core Oracles \/ Action](datasworn:oracle_rollable:starforged\/core\/action)" result="Deflect" roll=31
                    oracle name="[Core Oracles \/ Theme](datasworn:oracle_rollable:starforged\/core\/theme)" result="Tool" roll=90
                }
                oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Defeat a rival" roll=17
            }
        }
        oracle name="[Character Oracles \/ Character Goal](datasworn:oracle_rollable:starforged\/character\/goal)" result="Pay a debt" roll=46
    }
}
```
