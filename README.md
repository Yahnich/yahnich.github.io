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

## General
- Respawn mechanic changed, instead of dropping a Tombstone, you come back to life automatically after 30 seconds in Normal, 60 seconds in Hard, 90 seconds in Challenger and 180 seconds in Nightmare
- Reversed the player count for maps. Normal now has 10 players, Hard has 8, Challenger has 6 and Nightmare has 5.
- Increased player count health scaling
- All heroes have tree-walking
- Added more trees to Nightmare
- Added cast indicators for boss abilities

## Hero Scaling
- You now gain an additional ability point at level 17, 19 21, 22, 23 and 24 to level up abilities, on top of the free increase in +Attributes
- Melee heroes no longer have a 80% chance to block 35%/85% of hero/creep damage or a guaranteed 50% damage block against creeps.
- Melee heroes now have 4 additional armor.
- Illusions fixed, now have the same stats (note that illusions do not benefit from melee heroes' magic resist bonus, as it is not base magic resist)
- Reduced all hero magic resistance from 25% to 15%
- Reduced melee magic resistance bonus from 20% to 12% (base magic resistance from 40% to 25%)

## Ability Scaling
- Drastically reworked, fuck it.
- Ability damage and healing now scales linearly instead of exponentially (doubling each time). This applies to items too. Too many items and abilities are rescaled to note them all down.
- Ex. Lina Dragon Slave impact damage from 1200/2000/3500/6500/12500/20000/35000 to 750/1500/2250/3000/3750/4500/5250
- Leveling up now increases ALL ability damage (including item damage) by 20%.
- Ex. Lina Dragon Slave would deal 750/1500/2250/3000/3750/4500/5250 at lv1, 2250/4500/6750/9000/112500/13500/15750 at lv11 and 6750/13500/20250/27000/33750/40500/47250 damage at lv41 (end of game)
- Spell amplification from primary attribute from 0.8% to 0.6%
- Spell amplification from all attributes for Universal Heroes from 0.4% to 0.3%
- Spell amplification from Intelligence from 0.4% to 0.3%
- Summarized, damage floors are higher, damage ceilings are about the same.
- Talents that give attributes (stats, damage, health, regen) now scale with your level as well, talent values rescaled to match progression.

## MMR
- MMR is now a static +10/-20, increasing by +5/-10 for each difficulty (Nightmare is +25/-50). Abandons lose you triple the MMR
- The MMR lost reduces linearly each round completed, up to -0 if you lost the last round
- Calculations concerning missing players and abandons are still active

## Restoration
- Re-enabled out of combat regeneration
- Regeneration increases by 1% every second, but starts at 3% instead of 5%, caps at 10%

<div align="center">
  <h1>Items</h1>
</div>

## Abyssal Blade
- Upgrades to Tier 5 using Scythe and Reaver upgraders.
- When Abyssal Blade bashes, deals base damage + percentage of your Strength magical damage to all units in 325 radius. All units hit by this damage are stunned for 2 seconds.
- Abyssal active Bashes the targeted unit.
- Abyssal Blade's damage block is now increased by 30/40/55/75/100% of your Strength.

## Armlet
- Health drain per Strength provided from 1 to 2.5

## Blink Treads
- No longer goes on cooldown when taking damage. Blinking during the damage cooldown will execute all effects at your position, but will not teleport you (Overwhelming Stance will deal damage, Swift Stance will buff you and Arcane Stance will heal you and restore mana)

## Fallen Sky
- No longer put on cooldown when taking damage. Blinking during the damage cooldown will summon a Meteor on your location, but will not teleport you

## Hand of Midas
- Removed.

## Heart of Tarrasque
- Bonus HP Regen Per Strength from 0.3/0.5/0.7/0.9/1.1 to 0.15/0.3/0.45/0.6/0.8
- Active now gives +25/30/40/55/75% bonus health and health regeneration from Strength instead of doubling the health (regeneration) provided by Heart.

## Lotus Orb
- Rescaled cooldown from 15/14/13/12/11 to 25/20/15/10/5
- Rescaled duration from 6 to 25.

## Manta Style
- Upgrades to Tier 5 using Eaglesong and Ultimate Orb upgraders.
- Melee illusion damage is 33/45/57/69/81%
- Ranged illusion damage is 28/36/44/52/60%
- Illusion damage taken is 300/250/200/150/100%

## Octarine Core
- Removed Ultimate Orbs from recipe, cost unchanged
- Refresh active cooldown from 195 to 195/180/165/150/135

## Scythe of Vyse
- Upgrades to Tier 5 using Mystic Staff and Ultimate Orb upgraders
- Targets 1/2/3/4/5 units. If no more new units are found, can bounce to units already Hexed, increasing the Hex's duration by 0.5 seconds. Can Hex a single unit up to 3.5/4.0/4.5/5.0/5.5 seconds
- Hex now Breaks units.

## Signet of Destiny
- Now upgrades using lower tier Mystic Staff Upgraders + Ultimate Orb Upgraders. Stats provided changed accordingly.

## Silver Edge
- Reworked recipe, now includes Skull Basher in its build-up.
- Upgrades to Tier 5 using using Scythe and Reaver upgraders.
- On hit, deals bonus damage, stuns for 2 seconds and then slows and breaks for an additional 2 seconds.
- Grants a passive chance to Bash.

## Vladmir's Offering
- Downgraded Damage Upgraders by one tier, reducing overall price. Bonus damage changed accordingly

## Uber Dagon
- Removed Mystic Staff Upgraders from recipe. Orb Upgraders increased in tier. Stats provided changed accordingly.

## Neutral Items
- The stats of Neutral Items now scale with your level, keeping them relevant for longer.
- Stats rescaled.

## Consumable Items
- All consumeable items, like Faerie Fire, Healing Salve, Clarity, etc... active benefits now scale with your level.

<div align="center">
  <h1>Heroes</h1>
</div>

## Alchemist
- Chemical Rage health regeneration from 1000/3450/11000/30550/36625/42675 to 750/2000/4000/6000/9500/12500

## Abaddon
- Aphotic Shield's barrier no longer scales with spell amplification, damage dealt does scale with barrier now.

## Axe
- Re-enabled
- Axe has Rage now instead of Mana. Rage starts at 0 and is gained whenever Axe deals or takes damage. Maximum Rage is 100. Items cost 80% less mana as Rage.
- Berserker's Call costs 50 Rage
- Battle Hunger costs 25 Rage and cooldown reduced to 1 second.
- Culling Blade costs 100 Rage.

## Dark Seer
- Vacuum Radius from 400/425/450/475/500/525/550 to 325/400/475/550/625/700/775
- Wall of Replica now deals 250/400/550/700/850/1000 damage

## Pangolier
- Shield Crash now provides a base amount of barrier equal to the barrier per hero unit.

## Wraith King
- Mortal Strike critical multiplier from 150/200/250/300/350/400/450% to 300%
- Mortal Strike cooldown from 5.5/5.0/4.5/4.0/3.0/3.0/2.5 to 5.5/4.75/.0/3.25/2.5/1.75/1.0

<div align="center">
  <h1>Bosses</h1>
</div>

## Minions
- On Nightmare, minion units now spawn endlessly until all hero units have been killed. Waves affected: Kobolds, Slardars, Ogres, Axes, Dragons, Ursas
- Initial minion spawns and spawn rates reduced (less frontloaded)

## Troll Wave
- Troll Warlord now has Aghanim's Shard, granting a stacking chance to send additional projectiles in an AoE.

## Ursa Wave
- All units now have Overpower on top of Fury Swipes, except for Ursalings.
- Drow Boss removed.
- Beastmaster Boss no longer summons Ursas. Now has Inner Beast Aura, Howl, Primal Roar and Drums of Slom
- While at least one Ursa is alive, one Ursaling spawns every 30/25/20 seconds.
- Ursas have Earthshock (stuns instead of slows), Overpower, Fury Swipes and Enrage. Enrage can be dispelled.
- Fury Swipes can be dispelled, but when dispelled the debuff is returned at half stacks.

## Nyx Wave
- Psionic Assassin's now Burrows when he Impales. When the Impale ends, Psionic Assassin reappears, dealing damage to all units in range.
- Psionic Assassin has Mind Flare, targeting all units within 900 radius. Low base damage, high multiplier on damage dealt by Psionic Assassin within the last 15 seconds. Used off cooldown, unless no damage would be dealt.
- After taking 10% of his maximum health in damage, Nyx Assassin activates Reflecting Carapace, which deals 50% of all damage he takes back to the attacker. Lasts 2.5 seconds.
- When a unit dies to Nyx Assassin or his Reflecting Carapace ends, he goes invisible, 100% bonus phased movement speed and gains 80% damage resistance for 10 seconds, then runs towards the lowest health creature. While invisible, his next attack deals greatly increased damage.
- Added Psionic Scarab minion to the wave. Psionic Scarab has a single-target Mind Flare that is based off of total damage taken, rather than only damage dealt by Psionic Scarab.

## Warlock Waves
- Merged together. Warlocks spawn initially
- Warlock has a Vlads and Assault Cuirass.
- Warlocks have Fatal Bonds, Shadow Word, Upheaval and Chaotic Offering. Warlock summons Imps while channeling Upheaval, which run to the lowest health enemy within their search range and explode.
- Warlock Golems have no duration and last forever.

## Shadow Fiend & Shadow Demon Wave
- Shadow Demon protects Shadow Fiend, as long as Shadow Demon is alive, Shadow Fiend takes no spell damage and Shadow Demon takes 50% of the spell damage dealt to Shadow Fiend instead. The other 50% is spread all enemy units.
- Shadow Fiend protects Shadow Demon, as long as Shadow Fiend is alive, Shadow Demon takes no attack damage and Shadow Demon Fiend 50% of the attack damage dealt to Shadow Demon instead. The other 50% is spread over all enemy units.
- Shadow Fiend has 3 Razes, Necromastery, Presence of the Dark Lord and Requiem of Souls.
- Shadow Fiend will prioritize hitting creatures hit by Demonic Purge or Disseminate with attacks and razes.
- Necromastery increases Shadow Fiend's attack damage for each unit hit with his Razes instead.
- Requiem of Souls creates Shards of Mania for each unit hit, which grant allied units a chance to deal critical damage on hit and gain increased attack speed.
- Shadow Demon has Disruption, Disseminate, Shadow Poison and Demonic Purge. Shadow Demon will activate Shadow Poison as soon as Disseminate is available and a unit has at least 3 stacks or when a unit has 5 stacks. Checks for Disseminate cast first regardless.
- Disruption creates 3 Shard of Melancholy (cd scales with players), creeps that reduce the healing received from all units

## Shadow Fiend & Shadow Demon Wave
- Shadow Demon protects Shadow Fiend, as long as Shadow Demon is alive, Shadow Fiend takes no spell damage and Shadow Demon takes 50% of the spell damage dealt to Shadow Fiend instead. The other 50% is spread all enemy units.
- Shadow Fiend protects Shadow Demon, as long as Shadow Fiend is alive, Shadow Demon takes no attack damage and Shadow Demon Fiend 50% of the attack damage dealt to Shadow Demon instead. The other 50% is spread over all enemy units.
- Shadow Fiend has 3 Razes, Necromastery, Presence of the Dark Lord and Requiem of Souls.
- Shadow Fiend will prioritize hitting creatures hit by Demonic Purge or Disseminate with attacks and razes.
- Necromastery increases Shadow Fiend's attack damage for each unit damaged. Spell damage increases the attack damage 3x as much.
- Shadow Demon has Disruption, Disseminate, Shadow Poison and Demonic Purge. Shadow Demon will activate Shadow Poison as soon as Disseminate is available and a unit has at least 3 stacks or when a unit has 5 stacks. Checks for Disseminate cast first regardless.
- Disruption creates 3 Shades (cd scales with players), creeps that have no abilities but have a Skadi and steal 1 random passive from the targeted hero. Prioritizes units attacking Shadow Demon and then Shadow Fiend. Shadow Demon will attempt to move away afterwards.

## Necrophos Wave
- Has Poison Nova, Poison Attack, Death Pulse, Heartstopper Aura, Death Seeker and Reaper's Scythe.
- Poison Nova is cast every 30 seconds from Necrophos, as long as at least 1 unit will be hit by it. Additionally, any time any creature dies, including Plague Wards, a smaller Poison Nova explodes out of them. Debuffs don't stack, simply refresh. Is purgable.
- Reaper's Scythe targets all units on the map. Necrophos will use it as soon as at least one hero would be killed by it.
- Heartstopper Aura is global.
- Necrophos will cast Death Seeker on the enemy furthest away from him, global cast range.
- Necrophos will create three Plague Wards around a random unit every 10 seconds (cd scales with players), Plague Wards have Poison Attack.
- Other spells are cast off cooldown. Death Pulse and Reaper's Scythe have no mana cost.

## Doom Wave
- Has Devour, Scorched Earth, Infernal Blade and Doom.
- Will Devour a random creep if possible. Will summon Imp creeps every 15 seconds (cd scales with players). Every living Imp grants Doom +20% damage amplification and 20% damage resistance. If Doom devoured a creep with passive abilities, he gains their passives. If Devour is off cooldown for 15 seconds, Doom will target a hero instead, simply dealing damage to them instead. While Devour is active, Doom gains armor.
- Infernal Blade affects all units within 450 radius of the attacked unit.
- Doom causes a 600 unit radius around the targeted unit. Breaks, Mutes, Silences and prevents healing.

## Asura Wave
- Asura will now hunt down units more aggressively, instead of loitering around.
- Sleight of Fist is no longer a targeted ability. Instead, while attacking, there is a 20% chance will Sleight of Fist in a 800 radius around the attacked unit.
- Added some more Hell on Earth patterns.
- Asura's Shield no longer prevents all damage. Instead, he gains a regenerating barrier for 15 seconds. No longer linked to his mana, he casts it off-cooldown instead. When the barrier breaks, it stops regenerating and stuns Asura for 5 seconds. Asura deals damage in a 1200 radius while the Barrier is active.
- When Asura's Shield ends, whether by expiring or being broken, a Gate will be left behind. If the Gate is not destroyed within 5 seconds an Underlord General appears.
- Asura has a new ability: Obliterate (unit-target). Asura marks a target and they take 100% increased damage and are slowed by 100%. Will prioritize Soulbound targets.
- Underlord Generals have Pit of Malice, Firestorm and Atrophy Aura. Any unit killed under Atrophy Aura permanently increases Underlord General's damage. 50% of this damage is shared with Asura.
- Asura creates a Grim Cleric every 20 seconds (scales with player count). Grim Cleric has Soulbind, Dark Portrait, Ink Swell, Phantom's Embrace and Stroke of Fate. Will prioritize Soulbound targets.