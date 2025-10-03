> EBF 2.1.0 - 03/10/2025
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Health
- Bonus health from strength increased from 22 to 100
- Primary attribute no longer provides bonus health.
- Heroes now start with 6000 bonus health, rather than 600. Still scales with hero power.
- Bonus health and regeneration provided by items has increased, referenced later. (Ex. Lucky Dice bonus health from 500/875/1530/2675/4680 to 5000/8750/15315/26795/46895)
- Certain hero abilities based on health and healing have been changed, referenced later.  (*hero healing and barrier has been doubled across the board, self-percentage based ability damage, like Bloodseeker Ocelotl Sanguivore aura, divided by 5 or 10)
- Spell amplification and base spell power now affects healing and barrier (same behavior as damage).

## Game Penalties
- There are now game penalties for staying AFK. If you do not perform any orders, are disconnected or take/deal no damage for 5 minutes (being dead does not count towards this), you are considered to have abandoned. You will not obtain MMR and will lose 30 instead, you will no longer be considered an active player and your hero will be removed from the game. These are separate checks, each with their own timer.
- If you do not deal enough damage in a round, that round will not apply your MMR progression. This means it would take 6 rounds (or more) to obtain 5 MMR, instead of the normal 5 MMR every 5 rounds. This amount of damage is low enough to not impact active players. Performing no cast or attack orders during a round will also discredit you from the round in this way.

## Attribute Scaling
- Armor from agility reduced from 0.015 to 0.008
- Attack speed from agility reduced from 0.1 to 0.05

## Buff/Debuff/Modifier Duration Amp
- Changed how these properties are handled, they now directly affect the ability's value additively (was multiplicatively before); this means it now works when refreshing durations and is immediately visually updated on the item/spell.

## Keyword Passives
- For visual clarity, active hero abilities with a passive effect have gained Keyword Passives to quickly indicate intent. This does not change how any existing ability works and is simply for visual clarity on what game events occur.
- Added Morbid (Type): Morbid passives trigger whenever any unit dies in range (1200 aura range standard). Typically this denotes the team and the type of the unit that dies to trigger the effect. For example, Morbid (Hero), triggers whenever any Hero dies, while Morbid (Enemy Hero) triggers only when enemy Heroes die.
- Added Refresh: Refresh passives trigger whenever the ability's cooldown ends.
- Added Hurt (Source): Hurt triggers whenever a specified unit takes damage. For example, Hurt (Self) passives such as Centaur Warrunner's Return only trigger when the owner is damaged, while Hurt (Allies) passives trigger whenever any ally takes damage.
- Added Strike (Target): Strike triggers whenever you attack a unit of the specified type (if any). For example, Bounty Hunter's Jinada's gold steal is a Strike (Hero) trigger.
- Added Heal (Target): Heal triggers whenever the specified unit is Healed. Lifesteal and Health Regeneration are not Heals.

<div align="center">
  <h1>Items</h1>
</div>

## Artifacts
- Artifact of Shields initial value from 2000 to 6000
- Artifact of Shields bonus per threshold from 1 to 3
- Artifact of Balance seconds per gain from 5 to 10

## Blood Gem
- Reworked active: "Crystallize Blood - For 8 seconds, this item Lifesteals from damage you take, instantly turning it into False Barrier"
- Duration and cooldown unchanged.

## Monkey King Bar
- Removed bonus agility
- Now grants 20/35/61/107/188 bonus attack speed
- Proc chance rescaled from 80% to 40/55/70/85/100%
- Proc damage rescaled from 350/700/1050/1400/1750 to 700/1400/2100/2800/3500

## Items - Health Rescaling
- Cloak of the Protector: Bonus health from 325/570/1000/1750/3060 to 1500/2625/4595/8040/14065
- Cloak of the Protector: Bonus health regeneration from 25/45/78/135/235 to 140/245/430/750/1315
- Cloak of the Protector: Aura health regeneration from 15/26/45/78/136 to 25/44/77/134/235
- Cloak of the Protector: Barrier from 1500/3000/4500/6000/7500 to 4500/9000/13500/18000/22500
- Conqueror's Splint: Bonus health regeneration from 25/45/80/140/245 to 40/70/123/215/375
- Blink Threads: Arcane Blink health restored from 1000/2000/3000/4000/5000 to 2500/5000/7500/10000/12500
- Lucky Dice: Bonus health from 500/875/1530/2675/4680 to 5000/8750/15315/26795/46895
- Lucky Dice: Bonus health regeneration from 20.5/35.5/62.0/108.5/190 to 120/210/365/645/1125
- Signet of Destiny: Bonus health from 325/570/1000/1750/3065 to 4250/7435/13015/22775/39860
- Signet of Destiny: Healing per second from 100/200/300/400/500 to 400/800/1200/1600/1800
- Spear of Justice: Bonus health regeneration from 37.5/65.5/114.75/201/351.75 to 75/130/230/400/705
- Unhallowed Icon: Bonus health from 450/785/1375/2405/4210 to 2500/4375/7655/13400/23450
- Unhallowed Icon: Bonus health regeneration from 40/70/125/220/385 to 60/105/185/320/565
- Force Boots bonus health from 600/1050/1835/3210/5620 to 1750/3060/5360/9380/16415
- Fallen Sky bonus strength from 20/35/61/107/187 to 31/54/95/166/291
- Fallen Sky bonus agility from 20/35/61/107/187 to 6/11/18/32/56
- Fallen Sky bonus intelligence from 20/35/61/107/187 to 24/42/74/129/225
- Fallen Sky no longer provides bonus health regeneration.
- Fallen Sky no longer provides bonus mana regeneration.
- Fallen Sky now provides 10/17.5/30.6/53.6/93.8% spell amplification.
- Lotus Orb bonus health regeneration from 20.5/35.8/62.6/109.5/191.5 to 65/114/199/348/610
- Bloodthorn bonus health regeneration from 30/52.5/92/161/282 to 65/114/199/348/610
- Phylactery bonus health from 450/785/1375/2405/4210 to 2000/3500/6125/10720/18760
- Hurricane Pike bonus health from 500 875 1530 2675 4680 to 2000/3500/6125/10720/18760
- Heart of Tarrasque bonus health per strength from 2/3/5/8/14 to 6/10/18/32/56
- Heart of Tarrasque bonus health regeneration per strength from 0.1/0.17/0.3/0.52/0.91 to 0.5/0.85/1.5/2.7/4.5
- Armlet of Mordiggian bonus health regeneration from 40/70/125/220/385 to 50/87.5/153/268/469
- Gleipnir bonus health from 450/790/1380/2415/4225 to 3500/6125/10720/18760/32825
- Eye of Skadi bonus health from 500/875/1530/2675/4680 to 2500/4375/7655/13400/23450
- Refresher Orb bonus health regeneration from 90/158/276/482 to 180/315/551/965/1688
- Octarine Core bonus health from 675/1180/2065/3610/6320 to 6250/10935/19140/33500/56820
- Octarine Core no longer provides bonus health regeneration.
- Eternal Shroud bonus health from 500/875/1530/2675/4680 to 2500/4375/7655/13400/23450
- Bloodstone bonus health from 550/965/1690/2950/5165 to 5000/8750/15315/26800/46900
- Solar Crest bonus health from 575/1000/1750/3080/5390 to 2000/3500/6125/10720/18760
- Solar Crest active barrier from 2000/4000/6000/8000/10000 to 4000/8000/12000/16000/20000
- Guardian Greaves aura health regeneration from 20/40/60/80/100 to 25/44/77/134/235
- Guardian Greaves critical health aura health regeneration bonus from 100/200/300/400/500 to 120/210/368/643/1125
- Guardian Greaves health restored from 2500/5000/7500/10000/12500 to 7000/14000/21000/28000/35000
- Aeon Disk bonus health from 550/965/1690/2950/5150 to 2500/4375/7655/13400/23450
- Glimmer Cape magic barrier from 3000/6000/9000/12000/15000 to 6000/12000/18000/24000/30000
- Soul Ring mana gain per health threshold lost from 8 to 2
- Shiva's Guard bonus health regeneration 25/44/77/134/234 to 50/87.5/153/268/469
- Nullifier bonus health regeneration 40/70/122/213 to 60/105/184/322/563
- Seeds of Serenity bonus health regeneration from 20/35/61/107/188 to 40/70/122/213/375
- Seeds of Serenity Verdurous Dale health regeneration from 50/100/150/200/250 to 100/200/300/400/500. Reminder that this is affected by base spell power now.
- Safety Bubble barrier from 1000/2000/3000/4000/5000 to 2000/4000/6000/8000/10000
- Safety Bubble bonus health regeneration from 40/70/122/213 to 50/87.5/153/268/469
- Duelist Gloves bonus health from 600/1050/1835/3215/5625 to 3000/5250/9190/16080/28140
- Fairy's Trinket bonus health from 400/700/1125/2145/3750 to 500/875/1530/2680/4690
- Dragon Scale bonus health regeneration from 25/44/77/134/235 to 50/87.5/153/268/469
- Imp Claw's critical hit can no longer miss.
- Dandelion Amulet magic barrier from 1500/3000/4500/6000/7500 to 3000/6000/9000/12000/15000
- Gale Guard barrier from 2500/5000/7500/10000/12500 to 5000/10000/15000/20000/25000
- Nemesis' Curse bonus health regeneration from 20/35/61/107/188 to 60/105/184/322/563

## Paladin's Sword
- New Brawler item
- Grants +100/175/306/534/938 bonus health regeneration.
- Grants +8/14/24.5/42.75/75% restoration amplification.
- Has the following passive: "Blade of Valor - You gain 0.3/0.5/0.9/1.6/2.8 bonus damage for every point of health regeneration you have."

## Spear of Poseidon
- New Assassin item.
- Grants 16/28/49/86/150 bonus all-stats.
- Grants +50/88/153/268/469 bonus damage.
- Has the following passive: "Oceanic Might - Every 8/7/6/5/4 seconds, the next attack you land unleashes a crashing wave that passes through all enemy units, rooting them and dealing 4% of your current health as Physical damage."

## Breath of the Anemoi
- New Speedster item.
- Grants +20/30/40/50 bonus movement speed.
- Grants +20/40/60/80 max movement speed.
- Grants +8/14/24.5/42.75/75% spell amplification.
- Has the following passive: "Breezesoul - You gain 0.2/0.31/0.77/1.34/2.35 health regeneration and 8/14/25/44/75 health for each point of movement speed. Improves with hero power."

## Mageweave Veil
- New Evoker item.
- Grants 2000/3500/6125/10725/18750 bonus health
- Grants +8/14/24.5/42.75/75% spell amplification.
- Has the following passive: "Arcane Surge - When you Cast, you take Pure damage equal to 1% of your maximum health, but when you gain your casting resource, you Regenerate for 10/18/31/54/94x the mana gained."

## Azureblood Bowl
- New Commander item.
- Grants 32/56/98/172/300 bonus all-stats.
- Has the following ability: "Quintessence of Life - Any time an allied Hero is Healed, this item gains a charge. When you cast this item, up to 10 charges are consumed for each allied Hero in range. For each consumed charge, a random Hero within 900 units of you gains 0.1/0.2/0.3/0.4/0.5 seconds of invulnerability, up to a maximum of 10 times. Reapplying the buff increases its total duration accordingly. This has a 10 second cooldown."

## Bloodfloe Pendant
- New Tactician item.
- Grants +8/14/24.5/42.75/75% spell amplification.
- Grants +60/105/184/322/563 bonus health regeneration.
- Has the following passive: "Bloodfloe - When an allied Hero restores 25% of their maximum health, they erupt in a 350 AoE glacial explosion. This Roots and Disarms all units in the AoE for 0.5/0.75/1.0/1.25/1.5 seconds."

<div align="center">
  <h1>Heroes</h1>
</div>

## Arc Warden
- Removed all DOTA 2 facets, Aghanim's Scepter and Shard.
- Balance of Power: New innate, Arc Warden gains 4 all-stats every 20 seconds.
- Flux: No longer disabled when affected units are near their allies
- Tempest Double: Behavior returned to No-Target, Tempest Double spawns next to Arc Warden.

## Arc Warden - Disharmonious
- Flux: Silences by default. If the target is alone, Flux roots them for the entire duration of the ability. Rooted targets take 2x more damage.
- Magnetic Field: Self target ability. Provides bonus attack speed, attack range, and projectile speed to units inside the bubble.
- Spark Wraith: No longer targets a unit. Instead, is a ground target ability that attacks all targets in its AoE for 80% of Arc Warden's damage every 3 seconds.
- Tempest : Grants Arc Warden and his double a Double Damage rune for 8 seconds.
- Lv25 Talents. +30 Second Power Rune/Flux Infinite Duration
- Lv20 Talents. Flux Pure Damage/-1.5s Spark Wraith Attack Interval
- Lv15 Talents. Magnetic Field 2x Buffs/+20% Spark Wraith Damage
- Lv10 Talents. Magnetic Field gives +10 Magic Resistance/+6s Tempest Double Duration

## Arc Warden - Unitary
- Flux: Flux is now an AoE spell. Damage is increased per unit nearby that is also affected by Flux.
- Magnetic Field: Ground target ability. Creates a bubble that roots enemies inside. If there are enemies inside the bubble that are affected by Flux, Flux's duration is increased by 0.5s. Enemy Magic Resistance is reduced inside the bubble.
- Spark Wraith: Now does AoE damage. 1 Spark Wraith targets 2 enemies in range.
- Tempest Double: Grants Arc Warden and his double an Arcane rune for 8 seconds.
- Lv25 Talents. +30 Second Power Rune/Flux does 2% of the target's Current HP every tick.
- Lv20 Talents. Flux Pure Damage/Spark Wraith Pure Damage
- Lv15 Talents. +150 Magnetic Field AoE/+50% Spark Wraith Damage
- Lv10 Talents. +5% Magnetic Field Magic Resistance Reduction/+6s Tempest Double Duration

## Alchemist
- Greevil's Greed (Opus of Panacea): Bonus spell amplification from 1% per 1000 gold to 1.5% per 100 gold
- Greevil's Greed (Opus of Azoth): Bonus attack speed from 1 per 1000 gold to 2 per 100 gold
- Acid Spray: Damage per second from 250/300/350/400 to 300/500/700/900
- Acid Spray (Opus of Panacea): Now increases armor reduction by +1
- Acid Spray (Opus of Chrysopoeia): Linger duration from 5 to 5/10/15/20
- Acid Spray (Opus of Azoth): Now increases damage by +25%
- Unstable Concoction (Opus of Panacea): Barrier granted increased from 750/1250/1750/2250 to 1500/3000/4500/6000
- Corrosive Weaponry (Opus of Chrysopoeia): Stacks per second from 2 to 3.
- Berserk Potion (Opus of Panacea): Cooldown reduced from 35 to 25  
- Berserk Potion (Opus of Panacea): Duration from 8/10/12/14 to 14
- Berserk Potion (Opus of Panacea): Attack speed bonus from 30/40/50/60 to 60/100/140/180
- Chemical Rage (Opus of Panacea): Now increases duration by 10/15/20 (to 40/45/50).
- Chemical Rage (Opus of Azoth): Now lowers base attack time by 0.1
- Chemical Rage (Opus of Azoth): Bonus damage per second from +2.5% to +2.5/3.0/3.5%
- Chemical Rage (Opus of Chrysopoeia): Aoe bonus from 25/75/125 to 75/125/175 
- Chemical Rage (Opus of Chrysopoeia): Health bonus from 2000/3500/5000 to 3000/5500/8000

## Anti-Mage
- Persecutor: No longer degrades as you deal damage. Instead, you lose 10% of the amount every second after 1.5 seconds of delay.
- Persecutor (Path of Ascetic): Anti-Mage constantly gains barrier, up to a maximum based on Persecutor's current value and capped at a percentage of Anti-Mage's maximum health.
- Persecutor (Path of Ascetic): Barrier maximum from 200% to 10x.
- Counterspell (Path of the Ascetic): Reflection damage now applies to all damage taken while active, rather than just Counterspell's barrier.
- Mana Void: Now deals 1000/2000/3000 base damage

## Axe
- Coat of Blood reworked into Blood Forged Axe: Each time Axe is damaged or deals damage, all damage he deals is increased by 1% for 6/8/10/12 seconds. Has a 0.25 second internal cooldown.
- Blood Forged Axe (Jofurr): Blood Forged Axe also reduces all damage taken by Axe by the inverse amount (dealing double damage = taking half damage).
- Blood Forged Axe (Berserker): Blood Forged Axe grants 8/10/12/14 bonus attack speed per stack.
- Blood Forged Axe (Skald): Blood Forged Axe grants 0.75/1/1.25/1.5% heal amplification and modifier duration amplification. *(all buffs and debuffs are modifiers.)*
- Berserker's Call: Now also improves Blood Forged Axe's bonuses by 25/50/75/100%
- Berserker's Call: Bonus armor from 12/13/14/15 to 15/20/25/30
- Berserker's Call (Jofurr): Removes Blood Forged Axe's internal cooldown now instead of increasing Coat of Blood's bonuses.
- Berserker's Call (Berserker): Grants 10/15/20/25% bonus movement speed and evasion now instead of granting bonus attack speed. 
- Berserker's Call (Jofurr): Increased lifesteal from 5% to 8% and lifesteal bonus per stack from 1% to 2%
- Counter Helix: Internal cooldown from 0.3 to 0.25.
- Counter Helix: Radius increased from 300 to 400.
- Counter Helix (Jofurr): No longer applies stacking attack damage reduction. Instead, units hit by Counter Helix are Slowed by 25/50/75/100%.
- Counter Helix (Berserker): Now increases Counter Helix damage from 1000/1200/1400/1600 to 1000/1500/2000/2500
- Counter Helix (Skald): Now applies a stacking attack damage reduction. Units hit by Counter Helix deal 5% less attack damage per stack. Can stack up to 10 times, refreshing each time.
- Culling Blade: Cast behavior changed, now always refreshes his Blood Forged Axe stacks, instead of only on kill. Additionally, targeting creeps and Illusions does not put this ability on cooldown. 
- Culling Blade: Added a Morbid (Hero) keyword passive, which instantly Refreshes Culling Blade and causes its next cast to grant a permanent stack of Blood Forged Axe.
- Culling Blade: Added a Refresh keyword passive, when Culling Blade's cooldown ends for any reason, Axe gains 40 Rage and shares the effects of Blood Forged Axe with all allies in 900 units of him.
- Culling Blade: Blood Forged Axe stacks from 5/10/15 to 10 (Jofurr from 15/25/35 to 15)
- Lv10 Left Talent: +10 Berserker's Call Armor/Lv10 Right Talent: +50% Berserker's Call Bloodforged Axe Bonus.
- Lv15 Left Talent: -20% Battle Hunger Cooldown/Rage Cost/Lv15 Right Talent: +20% Counterhelix Damage
- Lv20 Left Talent: Berserker Call Applies Battle Hunger/Lv20 Right Talent: +0.5% Bloodforged Axe Damage Increase
- Lv25 Left Talent: +100% Culling Blade Bloodforged Axe Stacks/Lv25 Right Talent: Berserker's Call Feel No Pain (Axe is Debuff Immune and gains 100% damage resistance which reduces to 0% logarithmically over time.)

## Bloodseeker
- Sanguivore (Ocelotl): Reduced damage per missing health from 10/12/14/16% to 7/9/11/13%
- Bloodrage: Attack Speed Talent bonus from +25 to +50
- Bloodrage (Cuauhtli): No hero multiplier from +50% to +150%.
- Bloodrage (Cuauhtli): No hero radius from 500 to 150
- Bloodrage (Ocelotl): Maximum barrier from 80/100/120/140% to 60/80/100/120% of missing health.
- Bloodrage (Ocelotl): Barrier decay duration from 1.5 to 5
- Blood Rite (Ocelotl): Ritual radius from 1200 to 900.
- Thirst: Movement speed bonus from 40/70/100/130% to 20/40/60/80%
- Thirst: Movement Speed Talent bonus from +18 to +100%
- Thirst (Cuauhtli): Linger duration from 1.5 to 3/4/5/6
- Rupture (Cuauhtli): Attacked damage multiplier from +100% to +200%

## Chaos Knight
- Aghanim's Scepter and Shard effects.
- Removed all DOTA 2 facets.
- Reality Rift's debuff total duration now increases on refresh.
- Phantasm is no longer the default ultimate ability.

## Chaos Knight - Entropal
- Reins of Chaos: Chaos Knight gets bonus damage per illusion in a 400 radius around him.
- Chaos Bolt: On hit, creates a Phantasm illusion attacking the target that lasts 1.5 seconds.
- Reality Rift: Increases all existing illusions' lifetime by 6 seconds.
- Chaos Strike: Heals Chaos Knight and all of his controlled units in a 500 radius on a proc. Chaos Knight's heal values are 100% of the lifesteal and his illusions do 75% (based on their own lifesteal values).
- Phantasm: Illusions spawned increased by +1 at all levels.
- Lv25 Talents. Immortal Phantasm Illusions/Chaos Strike no minimum Crit Damage
- Lv20 Talents. +60% Reins of Chaos Bonus Damage/+20% Phantasm Outgoing Dmg
- Lv15 Talents. +30% Chaos Strike Crit Damage/Illusions throw Chaos Bolts
- Lv10 Talents. +4 Reality Rift Illusion Extension/Reins of Chaos gives 33 ASPD per illusion

## Chaos Knight - Uncertainoi
- Reins of Chaos: Chaos Knight gets a 17% damage bonus for every debuff on the enemy
- Chaos Bolt: On impact, has a 50% chance to bounce to a random enemy unit within cast range distance of the original target.
- Reality Rift: Has a 50% chance to Disarm or Silence the affected enemy unit. Lasts 50% of the duration.
- Chaos Strike: Has a 50% chance on proc to Break the unit for 1.25 seconds.
- Armageddon: New Ultimate ability. For 30 seconds, all units within 800 units of Chaos Knight have their chance-based effects are increased by 100/150/200% and their status and magic resistance reduced by 10/20/30%.
- Lv25 Talents. +100% Armageddon Chance Increase/+17% Reins of Chaos damage
- Lv20 Talents. Armageddon Affects Allies/Chaos Strike 6% chance to throw a Chaos Bolt at the target.
- Lv15 Talents. Reality Rift Disarms and Silences/AoE Chaos Bolt
- Lv10 Talents. Reality Rift Extra Debuff full duration/+1 Chaos Bolt Bounce

## Juggernaut
- Aghanim's Scepter and Shard effects.
- Removed all DOTA 2 facets.
- Healing Ward is now invulnerable.
- Omnislash: Duration from 3.0/3.25/3.5 to 3.0/3.5/4.0d
- Lv 25 Talents: Omnislash Second Wind | Blade Fury Invulnerability

## Juggernaut - Sohei
- Duelist: While attacking, all your cooldowns cool 12% faster.
- Blade Fury: Juggernaut can attack during Blade Fury.
- Healing Ward: Healing Ward pulses every 3 seconds, providing 30/60/90/120 bonus attack speed for 3.5 seconds to all allied units hit by the pulse.
- Blade Dance: Each time Blade Dance deals critical damage, you gain a stack of Bladeform. Each stack of Blade Form grants you 2% bonus base agility that lasts for 10 seconds, up to a maximum of 10.
- Omnislash: Juggernaut gains the Swift Slash sub-ability, has a 20 second cooldown. When activated, Juggernaut performs a 1/1.5/2 second Omnislash without bonus damage.
- Lv 20 Talents: +10 Bladeform Max Stacks | +1.5 Omnislash Attack Rate Multiplier
- Lv 15 Talents: Healing Ward Pulse gives 8% Total Outgoing Dmg | Blade Fury Applies Attack Modifiers
- Lv 10 Talents: +3% Duelist Cooldown Rate Reduction | +2% Blade Dance Blade Form Bonus Agility

## Juggernaut - Ronin
- Duelist: Units that attack you have a 12% chance to miss, which is increased to 24% if Juggernaut damaged the unit within the last 5 seconds.
- Blade Fury: Damage radius is increased by 100 and enemies hit have their movement speed slowed by 15/25/35/45% and attack speed by 30/50/70/90.
- Healing Ward: Healing Ward provides 3/5/7/9 bonus armor and 8/12/16/20% magic resistance for those in the aura.
- Blade Dance: Each time Blade Dance deals critical damage, you gain a stack of Ronin's Endurance. Each stack of Ronin's Endurance grants you 5% bonus restoration amplification that lasts for 10 seconds, up to a maximum of 10. 
- Omnislash: Omnislash duration increased to 4/5/6. Omnislash cannot end early, if there are no more viable units in radius, Juggernaut becomes invulnerable and hasted until a unit is found.
- Lv 20 Talents: +10 Ronin's Endurance Max Stacks | Omnislash target has its Total Outgoing Damage reduced by 8%
- Lv 15 Talents: Healing Ward Negative Aura | +100% Blade Fury Debuff Effects
- Lv 10 Talents: 6% Duelist Miss Chance | +5% Blade Dance Ronin's Endurance Restoration

## Kunkka
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Tidebringer: Now properly Kunkka's Innate. Does not require leveling, scales automatically based on Ghost Ship's level.
- X Marks the Spot: Removed.
- Captain's Rum: New Basic abiity - Kunkka takes a swig of his trusty Flask, gaining 20/30/40/50% damage reduction. Lasts 10 seconds. Once the buff expires, Kunkka is affected by a debuff that causes him to take the damage negated over 10 seconds, but this damage is not lethal. 30 second cooldown.
- Tidal Wave: Is now a basic ability. Applies debuffs that last for 3/4/5/6 seconds.
- Ghost Ship: No longer applies Captain's Rum to allies.
- Lv10 Right Talent: +120% Ghost Ship Damage
- Lv 20 Talents: Greater Torrents/2x Tidebringer Effects
- Lv 25 Talents: Ghost Ship Fleet/0 Cd Tidebringer

## Kunkka - Mariner
- Tidebringer: Enemies are mini-stunned for 0.4 seconds when hit by Tidebringer.
- Torrent: Creates 4 additional Torrents. Prioritizes enemies not yet within the radius of a Torrent, otherwise creates a total of 4 extra torrents on the cast point, each with a 4 second delay.
- Captain's Rum: Can be cast on enemies, reducing their Status resistance and increasing their damage taken by 20/30/40/50%. This damage is dealt as a seperate damage instance and Kunkka heals for 50% of the damage dealt.
- Tidal Wav: Reduces the Magic Resistance of all enemies hit by 10/12/14/16%.
- Ghost Ship: Stun duration increased to 3.6 seconds.
- Lv10 Left Talent: Captain's Rum Point Target AoE        
- Lv15 Talents: +10% Tidal Wave Magic Resistance Loss / +15% Rum Bonus Damage/Status Resist Loss
## Kunkka - Admiral
- Tidebringer: Kunkka heals for 10% of the damage dealt by each Tidebringer hit.
- Torrent: Allies standing in the Torrent when it erupts gain 4/7/11/14 Bonus Armor and 40% Bonus Movement Speed for 4 seconds.
- Captain's Rum: Can be cast on allies. Captain's Rum applies a basic dispel when applied and gives a 15% Movement Speed Bonus.
- Tidal Wave: Reduces the Attack Damage of units hit by 10/15/20/25%.
- Ghost Ship: Applies Captain's Rum's buff to all allies touched by the Ghost Ship.
- Lv10 Left Talent: Rum gives 10 Armor
- Lv15 Talents: +20% Tidal Wave Attack Dmg Reduction/ +25% Rum Damage Resistance
## Kunkka - Privateer
- Tidebringer: Every Hero hit reduces the cooldown by 0.4 seconds; every Creep hit reduces the cooldown by 0.1 seconds.
- Torrent: Units affected by Torrent take 500/1000/1500/2000 additional Physical Damage when they take damage.
- Captain's Rum: Grants 20/30/40/50% Total Outgoing Damage for the duration.
- Tidal Wave: Reduces the armor of enemies hit by 4.
- Ghost Ship: When the Ghost Ship crashes, it launches a Tidebringer centered on itself based on 125% of Kunkka's base damage. Does not work when stolen.
- Lv10 Left Talent: Rum gives 2000 Bonus Base Damage
- Lv15 Talents: +4 Tidal Wave Armor Reduction / +25% Rum Total Damage Bonus


<div align="center">
  <h1>Bosses</h1>
</div>

## Evasion
- Reduced Ranged Champion base evasion from 20% to 8%.
- Reduced Melee Champion base evasion from 20% to 14%.
- Every player in the game increases evasion by 0.5%.

## Kobold Round
- Kobold Warrior no longer has Howl, instead has Rally Troops. This is a 3/2/1/0.5s channeled ability, once activated, 2 Kobold Serfs are summoned for each Player.
- Kobold Overseer no longer has Speed Aura, Swiftness Aura and Packleader's Aura.
- Kobold Overseer now has Ripper's Lash as an item and has a new ability: "Herald's Banner - Kobold Overseer plants down a Banner with 1/1/2/2 Health per active Hero. This Banner grants all units +20/30/40/50% damage, 10/15/20/25 armor and 10/15/20/25% magic resistance. Lasts 20/30/30/40 seconds. 40s cooldown"