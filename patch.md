---
layout: page
title: Patch Logs
include_in_header: true
---
# Patch Logs


<br>


## 2.0.9
1. Navigator (Skill Rework)
     - Pushes the front enemies back (1/1.5/2/3) distance

2. Gambler
     - When the blocks are combined, there is a 50% chance to draw either a blue card (win) or a red card (hand).
     - The growth value according to the number of blocks has been removed.
     - Gain maximum (2/3/4/5) energy or -1 energy

3. Fortune teller
     - Use the skill on the target being attacked.
     - The skill activation rate has been increased to 100% at all levels so that players can use them strategically or in crisis situations.
     - Skill damage has been adjusted. (20%/30%/40%/50%)
     - The growth value (skill damage 5%) according to the number of blocks is applied.


<br>

## 2.0.8
2048 Heroes can quickly achieve 2048 blocks, or use high attack power to process waves to blow up the opponent's base.
You can win.

However, in the current block growth method, the process of increasing the number to achieve 2048 is the direction to increase the attack power.
It was difficult to break the strategy to achieve the 2048 block by using an aggressive deck, etc.

To improve this problem, the amount of increase in attack power when combining blocks has been modified as follows.
Through this, the closer to the achievement of the 2048 block, the higher the risk by lowering the overall attack power.
You can check the related details in the tutorial in Settings.

1. Block's attack power growth
- Previously: Increases attack power by 50% when combining blocks
- Modification: Increases attack power by 90% when first block is combined, then decreases sequentially by 80%, 70%...

As a result, the attack power of the entire board has been increased, and the stamina of monsters and bases has also increased.

2. Fixed wave difficulty
- Monster HP increase by stage: 25 -> 50
- Step-by-step boss monster HP increase: 50 -> 100
- Base health: 1024 -> 2048

Fixed damage to monsters and base health recovery skills have been adjusted.

3. Savior
     - HP recovery amount: 12, 14, 16, 20 -> 32, 34, 36, 40
4. Chef
     - HP recovery amount: 8, 10, 12, 16 -> 24, 26, 28, 32
5. Farmer
     - Additional damage: 20 -> 40
6. Mob
     - Additional damage: 20 -> 40
7. Rifleman
     - Additional damage: 40, 60, 80, 120 -> 80, 120, 160, 240
8. Vigilante
     - Additional damage: 4, 8, 16, 32 -> 20, 30, 40, 60
     - Level growth: 2 -> 10

Also, some character balance adjustments have been made.

9. Revolutionary (Version 1.2.2 Rollback)
     - Activation condition adjustment: 128, 64, 32, 16 -> 256, 128, 64, 32 by stage
10. Lord
     - Existing: When the number of enemies defeated reaches the combined number of blocks x 2, the number rises, additional damage per level
     - Fixed: When the number of enemies killed reaches 12, 11, 10, 8, the number increases, additional damage is removed
11. Alchemist
     - Activation period adjustment: every 24, 22, 20, 16 -> 1 energy every 20, 18, 16, 12 seconds
     
In addition, two new quests have been added.

## 2.0.7
Currently, puzzle-oriented play rather than wave theorem shows that it is powerful in PvP mode.
The following changes are being made to ensure strategy diversity.

1. Captain
     - Activation rate: 100%
     - Activation target: 3/4/6/99 target
     - Skill Ability: Gain 1 Energy for 2 seconds when stunned or an enemy in a stunned state is killed
     - Block Growth: Adds 0.5 seconds of stun time depending on the number of blocks

## 2.0.5
Currently, puzzle-oriented play rather than wave theorem shows that it is powerful in PvP mode.
The following changes are being made to ensure strategy diversity.

1. Wave Correction
     - Reduced wave start delay: 1 sec -> 0.3 sec

2. Skill Mechanism Fix
     - Heroes with skills (politics, revolutionaries) will no longer be activated by revolutionaries and speakers when N is achieved.
     - When an architect creates an empty block, citizens can appear

## 2.0.0
The season has just started with a time of 'wild' right now.

The season has begun.

As 'unity' became 'all consummation', everything was completed.
With advertising effects, passive, applied across the country.
To improve 'silence' adjusts 'petrification'.

1. 'Silence'-->'Petrification'
     - There are three dispositions of 'Petrification'.
     - The point of view of 'petrification' is 'thousand years', and 'thousand years' of 'coordinates' is 3 seconds.

The doctor is promoting the plague doctor. In the splendor of the hero, I was able to be with the heroes as well.

2. Becoming a Doctor
     - In episode N, this was instructed.

## 1.2.2
Based on tower defense, 2048 heroes is a strategic tower defense game where you overcome the opponent with your own strategy while solving puzzles with the skills of various heroes.

Use a hero with good attack power, such as a swordsman or a mob, to quickly organize the wave to press the opponent,
Achieve 2048 quickly through skills that increase the number of blocks such as pioneers and speakers
It was designed so that you can play various strategies by taking advantage of the personalities of the heroes.

However, due to the current wave design, the monster's HP is low.
It shows a relatively favorable appearance for puzzle play among tower defense play and puzzle play.
By improving this, the wave composition and hero's attack speed have been changed so that various play is possible.

1. Fixed wave difficulty
     - Movement speed: 3.4 -> 3.5
     - Health per wave: 10 -> 25
     - Monsters per wave: 10 -> 7
2. Modify Hero Stats
     - Attack speed: 0.5 times per second -> 1 time per second

In addition, the utilization of heroes using legendary-grade achievable skills is declining due to the high skill activation requirements.
In order to improve this, the attainment skill of the legendary level is also raised to the same level as that of the politician.

3. Revolutionary
     - Activation condition adjustment: 256, 128, 64, 32 by stage -> 128, 64, 32, 16
4. Captain
     - Activation condition adjustment: 256, 128, 64, 32 by stage -> 128, 64, 32, 16


<br>

## 1.2.1
1. Fixed wave difficulty
     - Movement speed: 3.5 -> 3.4
     - Generation cycle: 0.4 -> 0.35
2. Modification of block increase growth
     - Activation rate increase change: 10% -> 5% (Explore Team, Fortune teller, Diplomat, Merchant, Architect, Doctor, Speaker)
     - Activation rate increase change: 10% -> 3% (gambler, sailor, navigator)
     - Activation rate increase change: 10% -> 1% (carpenter)
     - Activation rate increase change: 1% -> 2% (patrol squad)
     - Activation range increase change: 10% -> 5% (Farmer, Mob)
3. Alchemist
     - Activation time adjustment: 28, 26, 24, 20 by stage -> 24, 22, 20, 16
4. Chef
     - Coefficient adjustment: 4, 5, 6, 8 -> 8, 10, 12, 16 by step
5. Fortune teller
     - Activation probability adjustment: 60, 80, 100, 100 by stage -> 60, 70, 80, 100
     - Damage adjustment: 30, 30, 30, 50 -> 30 fixed by stage
6. Soldier
     - Attack speed adjustment: 8, 16, 24, 32 by stage -> 8, 12, 16, 24
7. Lord
     - Additional attack power adjustment: 10, 20, 30, 50 by stage -> 4, 8, 12, 20
8. Gambler
     - Activation probability adjustment: 30, 40, 50, 50 by stage -> 30, 35, 40, 50
     - Acquired goods adjustment: Up to 3, 3, 3, 4 -> 3 fixed per stage
9. Savior
     - Coefficient adjustment: Step by step 8, 10, 12, 16 -> 12, 14, 16, 20
10. Sailor
     - Activation probability adjustment: 60, 70, 80, 100 by stage -> 30, 35, 40, 50
11. Carpenter
     - Activation probability adjustment: 10, 20, 30, 50 by stage -> 10, 12, 14, 16
12. Navigator
     - Activation probability adjustment: 20, 30, 40, 50 for each stage -> 30, 35, 40, 50


<br>

## 1.2.0
1. Captain
     - Skill Rate: 100%
     - Skill targets: according to a number
     - Energy: Available at number (256/128/64/32) or more
2. Justice
     - Skill probability increases with number
3. Vigilante
     - Increase in skill attack power decreases (4>2)
     - Smaller skill range
