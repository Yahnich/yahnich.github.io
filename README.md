> EBF 1.5.1 - 07/06/2024
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Attribute Scaling
- Reduced hero base health from 2000 to 120 (vanilla value)
- Reworked attribute gain scaling. Attribute gain from level no longer increases by 80% each level, instead the total gained attributes are affected by ability power retroactively. This includes the base attribute.
- Ex. Bane total strength: From +2.5/7/32.5/115/430/945/1660 total bonus strength at lv2/5/10/20/30/40 to 10.15/49.6/145.35/449.35/903.75/1507.35
- Attack speed from Agility from 0.75 to 0.25 to accomodate for the increase in stat gains at early levels. Reduced attack speed diminishing returns from 2x attack speed for every 5x Agility increase to x2 attack speed for every 3.5x Agility increase.
- Spell amplification from abilities no longer scales with ability power.

<div align="center">
  <h1>Items</h1>
</div>

## Radiance
- Radiance no longer grants evasion.
- Burn radius from 1200 to 700.
- Burn damage from 300/600/1050/1650/2400 to 200/400/700/1100/1600
- Now upgrades using Diadem. All Stats from 15/45/130/225 to 8/20/35/85/125

<div align="center">
  <h1>Heroes</h1>
</div>

## Morphling
- Removed Aghanim's Scepter and Aghanim's Shard effects from Morphling.
- Added third facet.
- Accumulation reworked: Provides Morphling with +2 Strength and Agility, which increases by +2 every level.
- Waveform no longer deals attack damage by default.
- Adaptive Strike (Agility) no longer has an Agility threshold. Instead, deals up to 500% bonus damage equal to the percentage of base Agility versus base Strength. You get maximum bonus damage at 90% Agility.
- Adaptive Strike (Strength) no longer has a Strength threshold. Instead, stuns for up to 500% longer equal to the percentage of base Agility versus base Strength. You get maximum bonus damage at 90% Strength.
- Adaptive Strike (Strength) base stun duration from 0.5 to 0.3/0.4/0.5/0.6/0.7/0.8/0.9.
- Equalize bonus Strength and Agility from 50/100/150/200/250/300 to 30/60/90/120/150/180

## Morphling: Flow
- Morphling's abilities are modified as follows when using this facet:
- Morphling's Primary Attribute is Agility
- Accumulation: Increases Agility gained to +4 and increases by +4 every level.
- Waveform: Applies an auto-attack dealing 200% damage to units hit.
- Adaptive Strike (Agility): Damage increased.
- Morph: While Morphing, reduces all of Morphling's cooldowns by 0.5/1.0/1.5/2.0/2.5/3.0/3.5 per second.
- Equalize: Bonus Agility from 30/60/90/120/150/180 to 50/100/150/200/250/300

## Morphling: Ebb
- Morphling's abilities are modified as follows when using this facet:
- Morphling's Primary Attribute is Strength
- Accumulation: Increases Strength gained to +4 and increases by +4 every level.
- Waveform: Now slows the attack speed of enemies hit by 40/50/60/70/80/90/100.
- Adaptive Strike (Strength): Stun duration increased and slows movement speed by 80% for 2.5/3.5/4.5/5.5/6.5/7.5/8.5 seconds afterwards (on max Strength).
- Morph: Morph costs no mana and can be used while stunned.
- Equalize: Bonus Strength from 30/60/90/120/150/180 to 50/100/150/200/250/300

## Morphling: Still
- Morphling's abilities are modified as follows when using this facet:
- Morphling's Primary Attribute is Universal
- Accumulation: Grants +2 Intelligence and increases by +2 every level.
- Waveform: Cooldown reduced by 4.
- Adaptive Strike (Agility): No longer puts Adaptive Strike (Strength) on a 3s cooldown. Always deals maximum damage.
- Adaptive Strike (Strength): No longer puts Adaptive Strike (Agility) on a 3s cooldown. Always applies maximum stun duration.
- Morph: Morph shift rate increased
- Equalize: Now grants 30/60/90/120/150/180 bonus Intelligence

## Shadow Fiend
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Shadowraze: no longer has stacking damage.
- Feast of Souls: no longer increases attack speed.
- Necromastery: Every 10 creeps kills, or 2 hero kills, increases the maximum stacks by 1.
- Necromastery: No longer provides bonus attack damag by defaulte.
- Presence of the Dark Lord no longer reduces armor by default.
- Presence of the Dark Lord: Reduced attribute is increased for 20/30/40/50/50/50/50 seconds on Hero kill and 2/3/4/5/5/5/5 seconds on Creep kill.
- Requiem of Souls: No longer fears or reduces magic resistance by default.
- Requiem of Souls: Now applies a debuff that doubles the strength of Presence of the Dark Lord's stat reduction. Debuff duration increases per line hit.
- Base attack time is now 1.7 by default.
- Shadowraze Applies Attack Damage talent replaced with -2s Shadow Raze cooldown.

## Shadow Fiend - The Psyche
- Increases Shadow Fiend's base movement speed to 350.
- Necromastery: Grants 0.25/0.75/1.0/1.25/1.5/1.75/2.0% spell amplification per stack.
- Shadowraze: Applies a stack to units hit that increases the damage they take from Shadow Fiend's spells by 25%.
- Feast of Souls: Grants 40/50/60/70/80/90/100 AoE bonus and on activation reduces all cooldowns by 9 seconds.
- Presence of the Dark Lord: Reduces magic resistance by 14/14/14/14/18/22/26% in an area of effect. Hero kills increase this reduction by 2%, Creeps increase it by 0.5%.
- Requiem of Souls: Requiem of Souls return to Shadow Fiend, dealing 40% of the damage on return. Cooldown reduced by 30s

## Shadow Fiend - The Ego
- Reduces Shadow Fiend's base attack time to 1.5.
- Necromastery: Increases attack damage by 5/15/20/25/30/35/40 per soul.
- Shadowraze: Applies instant attacks with bonus damage instead.
- Feast of Souls: Grants a 40% chance to deal 160/180/200/220/240/260% critical damage. First attack after activation is a guaranteed critical hit.
- Presence of the Dark Lord: Reduces armor by 4/4/4/4/5/6/7 in an area of effect. Hero kills increase this reduction by 2, Creeps increase it by 1.
- Requiem of Souls: Deals physical damage, and grants Shadow Fiend 40/60/80/100/120/140/160 bonus attack speed for 8 seconds.

## Shadow Fiend - The Id
- Increases Shadow Fiend's base armor by 4.
- Necromastery: Grants Shadow Fiend 0.15/0.25/0.3/0.35/0.4/0.45/0.5 armor and 2/4/5/6/7/8/9/10 health regeneration per stack.
- Shadowraze: Reduces attack speed of units affected by 40/50/60/70/80/90/100.
- Feast of Souls: Heals Shadow Fiend for 800/1400/2000/2600/3200/3800/4400 and provides 20/25/30/35/40/45/50% lifesteal from all sources.
- Presence of the Dark Lord: Reduces all outgoing damage of enemies by 14/14/14/14/18/22/26%. Hero kills increase this reduction by 2%, Creeps increase it by 0.5%.
- Requiem of Souls: You are Debuff Immune while casting Requiem of Souls, and enemies hit are Feared.

## Slark
- Agility gained per attack from 3 to 2
- Agility gained per hero kill from 1/3/5/7/9/11/13 to 1
- The permanent agility gained now retroactively benefits from ability power scaling, rather than only at kill time.

## Primal Beast
- Uproar bonus armor per stack from 5/10/15/20/25/30/35 to 2/3/4/5/6/7/8
- +20 Uproar Bonus Armor per Stack to +7

## Tidehunter
- Blubber now removes all debuffs after taking 15% of his maximum health.
- Kraken Shell no longer purges debuffs from Tidehunter.
- No longer makes Tidehunter immune to damage during the buff duration. Instead gives him 80% damage resistance.
- Kraken Shell cooldown from 5/4.5/4.0/3.5/3.0/2.5/2.0/1.5 to 4.0/3.6/3.2/2.8/2.4/2.0/1.6

## Bloodseeker
- Bloodrage allied duration from 8 to 10
- Thirst regeneration effect moved to Sanguivore, scales with Rupture.
- Sanguivore hero max health regeneration from 0.5/0.75/1.00/1.25/1.5/1.75/2.00 to 0.3/0.4/0.6/0.8/1.0/1.2/1.4%
- Creep healing percentage from 40% to 20%
- Thirst max bonus movement speed from 10/20/30/40/50/60/70% to 40/55/70/85/100/115/130%
- Blood Mist maximum barrier from 50% maximum health to 16%

## Witch Doctor
- Voodoo Restoration no longer deals damage by default. Voodoo Festeration allows Voodoo Restoration to deal 100% of its healing as damage, but prevents allied healing and only heals Witch Doctor (vanilla parity)
- +2%/0.5% Voodoo Restoration Max HP Heal/Damage to +0.5% Voodoo Restoration Max HP Heal.

## Bristleback
- Quill cooldown from 3 to 2
- Back damage reduction from 20/22/24/26/28/30/32% to 16/18/20/22/24/26/28%
- War Path bonus damage from 150/200/250/300/350/400 to 50/100/150/200/250/300
- War Path stack duration from 15/16/17/18/19/20 to 20
- War Path maximum stacks from 12 to 8/9/10/11/12/13

## Marci
- Attacks per flurry from 5 to 5/6/7/8/9/10
- Time between flurries from 1.5/1.25/1.0/0.75/0.5/0.25 to 1.5/1.4/1.3/1.2/1.1/1.0

## Silencer
- Glaives of Wisdom no longer gains Intelligence from creeps.
- Glaives of Wisdom Intelligence steal duration from 35 to 20.
- Aghanim's Shard Glaives of Wisdom intelligence steal duration bonus from +50 to +15

<div align="center">
  <h1>Bosses</h1>
</div>

## Granite Golem Round
- Uses Tiny's model now.
- Reworked Split, no longer triggers on death, instead, once a Granite Golem higher than Lv. 1 reaches 50% health, they are stunned for 1.5 seconds and gain 90% damage resistance. They then explode into 2 golems with 100%/110%/120%/130%  of the original golem's remaining health. Reduces the level of all their abilities by 1.
- Reworked Rock Toss. Now tosses 2/3/5/6 Mud Golems evenly in a 300/450/600/750 radius, scales upwards with additional players. Upon impact, the golems stun for 2 seconds and deal 20,000 damage to enemies in a 200 unit radius. No longer a tracking projectile. If an allied Golem is within 150/200/250/300 radius, they are tossed too, increasing the damage by 5000/10000/15000/20000 and the impact radius by 50/100/150/200. Lv3 and 4 Golems now have Tree Grab and cleave for 50/75%.
- Granite Golem now also has Avalanche. Deals 5000/7500/10000/12500 damage in a 300/450/600/750 unit cone.