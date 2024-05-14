> EBF 1.5.0 - 10/05/2024
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## General
- Certain item attributes now scale with ability power (strength, agility, intelligence, attack damage, spell amp, bonus health, bonus mana, health regen, mana regen)
- Rescaled item attributes according to this
- Leveling up an item increases the base attributes, and therefore the total amount given
- Removed upgrader items, upgrading is purely done via recipes
- All Hexes apply Break now
- Normalized XP rewards (no more random spikes, rewards are the same for all difficulties); overall this has led to a reduction in earlygame XP, but similar lategame XP.
- Normalized gold rewards, overall more gold in the game.
- Applied caps to unit summoning, cannot exceed a certain number of minions per round, scales based on player count
- Creeps no longer all spawn from the same spawner.


<div align="center">
  <h1>Items</h1>
</div>

## Blood Gem
- Added Soul Booster to the recipe, total cost unchanged

## Book of Knowledge
- New consumable added to the game: You can spend 5000 gold to gain 5000 experience.

## Conqueror's Splint
- Conqueror's Splint now applies an attack dealing 20% + 95 flat conditional damage as part of the Damage Return. Flat damage scales with upgrades
- Increased critical chance from 25% to 30% in line with vanilla.
- Increased critical chance against attackers from 30/40/50/60/70% to 40/50/60/70/80%
- Rescaled critical damage from 180/190/200/210/220% to 170/180/195/215/240%

## Martyr's Bulwark
- Reworked recipe: Now builds from Blade Mail, Maelstrom and a Diadem. Stats and price adjusted accordingly.
- Active reworked: now increases Chain Lightning's chance to 100% during the active effect for both attacks made by and dealt to you.

## Mjollnir
- Reworked active: Static Charge is now a no-target active that applies a buff on yourself that increases your attack speed and allows Mjollnir's chain lightning to bounce towards units it already bounced to. If no enemy units are in range, can bounce to allied units without damaging them.

<div align="center">
  <h1>Heroes</h1>
</div>

## Pudge
- Flesh Heap strength gain now scales with levels

## Hoodwink
- Acorn Shot returned to vanilla behavior
- Acorn Shot now bounces to a random position in the ground to plant a tree if there are no more valid targets. It can then target units it has already bounced to afterwards.

<div align="center">
  <h1>Bosses</h1>
</div>

## Gnolls
- **Reduced Maim damage per second from 180/200/220/240 to 75/100/125/150**
- **Reduced Maim attack speed reduction from 60 to 8/10/12/14**
- **Reduced Maim duration from 4.0 seconds to 2.5 seconds**

## Clockwork Mechas
- **Clockwork Droid Rocket Flare damage from 625 to 725**
- **Clockwork Mech Hookshot damage from 3250/3500/3750/4000 to 7500/7000/8000/8500**
- **Clockwork Mech Battery Assault damage from 180/240/300/360 to 650/700/750/800**

## Glacial Spirits
- New Round 12, between Ogres and Treants to break up the horde waves
- Spawns Lich creeps, who rush towards the nearest enemy and throw a Chain Frost towards them
- Spawns Subzero creeps, who casts Ice Vortex and Ice Blast with infinite range, does not attack or come closer to heroes unless attacked.
- Spawns Winter Wyvern hero, who has Arctic Burn, Splinter Blast and Cold Embrace. Cold Embrace works on enemies, stunning them and dealing damage to them instead of healing.

## Treants
- **Forest Guardian Nature's Grasp damage per second from 700/800/1000/1000 to 3500/4000/4500/5000**
- **Forest Guardian Leech Seed damage per second from 2750/3000/3500 to 6000/6500/7000/7500**

## Axes
- **Crimson Reaver Battle Hunger base damage per second from 1400/1500/1800 to 1750/2000/2250/2500**
- **Crimson Reaver damage from 2250/2750/3000 to 4000/4500/5000/5500**
- **Crimson Reaver Culling Blade damage from 16000/18000/20000/20000 to 40000/45000/50000/55000**
- **Crimson Gremlin Culling Blade damage from 3000/4000/4500/4500 to 5000/6000/7000/8000**
- **Made Crimson Reaver more patient.**

## Skeleton King
- **Skeletal Minion base health from 136000 to 256000**

## Trickster Dragon
- New Round 18, between Skeletons and Ursas
- Spawns Puck Bosses. Pucks have Illusory Orb, Waning Rift, Phase Shift and Dream Coil. Whenever Puck casts on of their abilities, an Illusory Puck minion is spawned that is a copy of Puck, but cannot cast
- Puck has Aghanim's Shard and Scepter
- **1.5.0a: Base health reduced from 35000000 to 25000000**
- **1.5.0a: Waning Rift damage reduced from 6000/7000/8000/9000 to 3500/4000/4500/5000**
- **1.5.0a: Waning Rift duration from 2.0/2.5/3.0/3.5 to 3.0**
- **1.5.0a: Ethereal Duplicate damage dealt from 60% to 40%**

## Ursine Warriors
- **Ursine Shaman Primal Roar damage from 6000/6500/7000/7500 to 24000/26000/28000/30000**
- **Ursine Shaman Drums of Slom damage from 3500 to 5000/6000/7000/8000**
- **Ursine Shaman Drums of Slom radius from 600 to 750**

## Infernal Duelist
- New Round 21, between Nyx Assassin and Warlock rounds
- Spawns one Infernal Duelist hero. Has Duel, Overwhelming Odds, Moment of Courage, Arena of Blood, God's Rebuke and Spear of Mars.
- Spawns Fallen Angel creeps. Fallen Angels have Mystic Flare.