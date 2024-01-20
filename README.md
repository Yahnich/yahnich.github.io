> EBF 1.4.0 - 17/11/2023
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Player Scaling
- Smoothed out unit count scaling per player, instead of only increasing in unit count until the 3x Unit Count multiplier is hit and then increasing stats, both stats and unit count increase together (unit count multiplier is still capped at 3x).

<div align="center">
  <h1>Items</h1>
</div>

## Armlet
- No longer silences you if you are below 50% of your maximum health.
- No longer triples in attack damage while toggled on. Instead double the attack damage while above 50% of your maximum health, which increases to triple when below 50%.

## Blood Gem
- Rescaled the max barrier from 20/40/60/80/100% to 10/15/30/60/100%.

## Ethereal Blade
- Fixed Ethereal Blade breaking abilities that go from single-target to AOE.

## Fallen Sky
- Fixed not properly providing passive stats besides Strength.

## Lotus Orb
- Now prioritizes hero units.

## Signet of Destiny
- Fixed health amp values.

## Monkey King Bar - Gungnir
- Now uses Eaglesong instead of Hyperstone in the build-up to Monkey King Bar
- Gungnir and up now grant Agility instead of Attack Speed and use Eaglesong upgraders
- Soulslayer now provides its benefits in a 350 AoE.

<div align="center">
  <h1>Heroes</h1>
</div>

## Bristleback
- Quill Spray mana cost from 35/55/70/90/105/125/140 to 60/65/70/75/80/85/90
- Quill Spray base damage from 280/405/560/1020/2000/3280/5210 to 280/405/550/1050/200/3250/4500
- Quill Spray stack damage from 315/395/475/660/990/1385/1915 to 175/225/475/675/900/1200/1600
- Quill Spray max damage from 2000/4000/6500/10000/15000/22500/32500 to 850/1600/2400/4500/8500/16000/30000
- Bristleback's Quill Spray is no longer a cone when activated through Bristleback.
- Aghanim's Scepter returned to vanilla

## Hoodwink
- Acorn Shot's planted tree is placed further away from its source.

## Riki
- Smoke Screen cooldown from 20/17/14/11/9.35/7.7/6.05 to 20/18.5/17/15.5/14/12.5/11
- Smoke Screen miss rate from 30/37.5/45/52.5/60/67.5/75% to 60%
- Creatures affected by Smoke Screen always trigger Cloak and Dagger's Backstab.
- Blink Strike now stuns instead of slows creatures in Smoke Screen
- Cloak and Dagger is now a basic ability instead of an ult.
- Agility bonus damage reduced from 1.4/1.8/2.2/3.0/4.0/5.5x to 0.8/1.0/1.2/1.4/1.6/1.8/2.0x bonus damage.
- Fade time from 4/3/2/1.75/1.5/1.25 to 4/3.5/3/2.5/2/1.5/1
- Tricks of the Trade is now an ultimate ability. Tricks of the Trade hits all units in its radius. Tricks of the Trade always Backstabs.
- Tricks of the Trade cooldown from 8 to 16.
- Tricks of the Trade bonus agility percentage from 70/75/80/85/90/95/100% to 80/100/120/140/160/180%
- Aghanim's Scepter now allows Tricks of the Trade to apply Blink Strike's effects, and last 1 more second.
- 8% Cloak and Dagger Movement speed to +25%.
- Tricks of the Trade Applies a Basic Dispel talent to Tricks of the Trade Cast While Stunned and Hard Dispels
- -3s Tricks of the Trade Cooldown to 37.5% Faster Tricks of the Trade (Cooldown and attack speed increased)

## Windranger
- Shackleshot no longer searches in a cone behind it. Now targets a random unit within range to bounce to.
- Shackleshot can bounce 3/4/5/6/7/8/9 times.
- Shackleshot stun duration from 3.8 to 1.9.
- Stun duration against creeps is doubled.
- Attacks made by Windranger against Shackled targets always deal 120/140/160/180/200/220/240% critical damage
- Powershot damage is no longer reduced by creeps.
- Windrun's cooldown now starts when Windrun ends.
- Windrun duration from 3/3.2/3.4/3.6/3.8/4.0/4.2 to 3/4/5/6/7/8/9.
- Windrun no longer gives Windranger evasion. Instead gives all allies within 325 units of Windranger evasion (including Windranger). This applies to Aghanim's Scepter's physical damage reduction.
- Focus Fire cooldown from 70/50/30/25.71/21.43/17.14 to 15
- Focus Fire duration from 20 to 10/12/14/16/18/20
- Focus Fire damage reduction from 30/30/30/30/23/16% to 30%
- -5% Powershot Damage Reduction talent to "50% Faster Powershot - Powershot's channel is reduced and arrow speed is increased"

<div align="center">
  <h1>Bosses</h1>
</div>

## Ogre Wave
- Troll Minion Cripple DPS from 1500 to 500.

## Axe Wave
- Returned Counterhelix

## Treant Wave
- Lesser Treants are no longer created by creeps, only by heroes
- Greater and Lesser Treants health and attack swapped (melee Lesser Treants now have more health and damage than the Greater Treants)
- Returned Nature's Grasp