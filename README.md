> EBF 1.4.1 - 17/11/2023
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
- Melee heroes now have 25% status resistance
- Melee heroes have 25% more health, increases health from all sources.
- Increased stat growth from +50% per level to +80% (as an example, Bane +stats at lv10/20/30/40 from 81.25/287/618.75/1075 to 115/430/945/1660
- Stats Increase talent from +25%/lvl to +35%/lvl (250% to 350% max)
- Starting a new round resets all cooldowns and ability charges.
- Normalized mana costs across heroes, no more heroes that randomly have 300-400+ mana cost basic abilities

<div align="center">
  <h1>Items</h1>
</div>

## Abyssal Blade
- Increased ranged bash chance from 10% to 20%
- Increased melee bash cooldown from 2.3 to 5/5/4.5/4.0/3.5/3.0
- Increased ranged bash cooldown from 2.3 to 9/9/8/7/6/5
- Bash proc damage increased from 500/800/1100/1400/1700/2100 to 500/835/1670/2920/4580/6670
- Bash strength damage increased from 0/80/90/100/110/120% to 0/140/150/165/185/210%
## Heart
- Active is no longer purgable once it makes you magic immune
## Butterfly
- Active is no longer purgable once it makes you magic immune

<div align="center">
  <h1>Heroes</h1>
</div>

## Sniper
- Headshot no longer knocks enemies back, roots them for the duration instead.
- Headshot chances over 100% now overflow and trigger another roll. If multiple Headshots proc, the damage and duration are multiplied by the amount of procs.
- Take Aim no longer sets Headshot chance to 100%, instead grants +60/70/80/90/100/110/120% Headshot Chance.
- Take Aim active attack range form 70/180 290/300/410/520/630 to 200
- Killing a hero unit with Assassinate refreshes all of Sniper's cooldowns and charges. Killing a creep unit causes the Assassinate projectile to bounce to the nearest unit, dealing 50% damage.
- Changed Aghanim's Scepter from "Causes Assassinate to fire quicker and stun the enemy target." to "Sniper Assassinates all units within 800 radius of the primary target."
- +100 Attack Range talent with +50% Passive & Active Take Aim Attack Range, moved back to Lv25

## Grimstroke
- Ink Swell now Basic Dispels on cast.
- Ink Swell now always deal maximum damage and stun duration.
- Shard causes Ink Swell to Hard Dispel on cast and Basic Dispel the target for the entire duration.
- Fixed Ink Swell not damaging creeps.

## Phoenix
- Fixed Supernova not taking damage from enemies.
- Supernova attacks to kill is now 30 at all levels. Hero units deal 3 damage to the Supernova.
- Supernova cooldown from 180 to 180/170/160/150/140/130
- Reworked Shard from: "" to "Phoenix can cast spells during Supernova and gains 50% spell amplification during Supernova."

## Mirana
- Starstorm base radius is equal to Mirana's attack range + 150.
- Units damaged by Starstorm are debuffed. When Mirana attacks a unit with this debuff, they are affected by a Lesser Starstorm that deals 75% and does not place the debuff, consuming the debuff. If the unit is hit by a spell, they are affeced by a regular Starstorm.
- Sacred Arrow projectile speed from 900 to 1200
- Sacred Arrow no longer applies bonus damage up to a maximum. Instead linearly increases the base damage by 10% for each 100 units traveled.
- Sacred Arrow projectile distance removed.
- Sacred Arrow damage from 600/1500/2400/3300/4200/5100/6000 to 1500/2400/3300/4200/5100/6000/6900
- Moonlight Shadow passive evasion fixed
- Moonlight Shadow now provides 15/20/25/30/35/40% magic resistance.
- +Evasion talent replaced with Moonlight Shadow provides a spell amplification bonus equal to 3x the evasion bonus.

## Lycan
- Summon Wolves' Wolves stats adjusted to the new scaling system.
- Aghanim's Shard replaced with "Howl is now a passive aura. Whenever Lycan deals critical damage, Howl fears all units."
- Shapeshift duration from 25 to 25/30/35/40/45/50
- Shapeshift cooldown from 125/110/95/89/83.5/78 to 95

## Invoker
- Cataclysm now works, targeting all Hero Units with two Sunstrikes.
- Forged Spirits Melting Strike now works on creeps.

## Lone Druid
- Spirit Bear now shares Lone Druid's base stat growth.
- Entangling Claws now works and scales properly.

## Broodmother
- 3 Simultaneous Web talent replaced with +35% Insatiable Hunger damage.
- Replaced Broodmother's Aghanim's Scepter effect from "Gain Spinner's Snare" to "Units lose 5% movement speed per second and take 1000 damage per second while in Broodmother's Webs. Once a unit has their movement speed reduced by 100% by the Web, they are rooted and disarmed for 2.5 seconds and get affected by Silken Bola."
- Broodmother Spiderlings and Spiderites now scale based on Broodmother's level

## Clockwerk
- Battery Assault now deals double damage to creeps (but not creep-heroes).
- Replaced Cogs with the Tech Barrier passive ability: Tech Barrier grants Clockwerk 2000/2500/3000/3500/4000/4500/5000 barrier against all damage each time he casts a spell for 5 seconds. While Overclocking is active, this amount is multiplied by 2.5x. The barrier does not stack.
- When a creature breaks Tech Barrier, it gets zapped for 500/1250/2000/2750/3500/4250/5000 damage and has its current mana burned by 35%.
- Debuff Immunity in Power Cogs talent replaced with 1.25 second Debuff Immunity When Activating Tech Barrier
- -3s Power Cogs Cooldown talent replaced with +25% Barrier From Tech Barrier 
- Overclocking no longer slows Clockwerk after it ends.
- Overclocking cooldown from 50 to 35

## Phantom Assassin
- Blur duration from 2.0/2.0/2.0/2.0/2.5/3.0/3.5 to 30.
- Blur's active effect is now temporarily disabled when attacking a hero unit. After 5/5/5/5/4.5/4.0/3.5, Blur's effect is restored.
- Aghanim's Scepter effect now properly refreshes all cooldowns when killing a hero-type unit
- Aghanim's Scepter gives Phantom Assassin a guaranteed Coup de Grace when killing a creep-type unit.

## Slark
- Essence Shift bonus stats now scale with levels
- Permanent agility from 1 to 10
- Essence Shift Duration from 20/40/60/80/80/80 to 20/25/30/35/40/40/40
- +50s Essence Shift Duration to +10s
- Effectively, this changes maximum agility gained at lv19 (assuming maximum attack speed) from 6000 to 10615


<div align="center">
  <h1>Bosses</h1>
</div>

## Harbingers
- Reduced spread damage from 16/18/20/22% to 8/9/10/11%
- The unit that dealt the damage takes twice the damage (16/18/20/22% for original damage dealer)
- Hitting a Harbinger with the correct damage category disables the cloak for that damage instance. This allows auto-attackers with mixed damage categories (Ex. Enchantress Impetus, , Monkey King Bar) to hit Shadow Fiend and allows spellcasters whose spells also apply an auto-attack (ex. Sniper Assassinate) to use their abilities without repercussions. This also allows magical attacks, which count as both attack and spell to hit either boss without consequences. Order matters, hitting Shadow Demon with Impetus will still reflect the auto-attack damage and hitting Shadow Fiend with Assassinate will reflect the initial spell damage.
## Psionic Scarab
- Reflecting Carapace now strong dispels.
- Reflecting Carapace now starts at 0% reflection and scales up to its maximum over the duration.
- Reflecting Carapace max reflection damage from 15/18/21/24 to 20/30/40/50%