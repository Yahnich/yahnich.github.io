> EBF 2.0.1 - 09/07/2025
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Season
- Ranks and MMR have been saved, all MMRs have been reset to 3000.

## General
- Removed base magic resistance from all heroes, melee heroes still receive 15% bonus magical resistance and intelligence still increases magic resistance.µ
- Reduced base mana regeneration from 10 to 5.
- Reduced all forms of gold income (round rewards, neutral camps, GPM), but also reduced item costs. 
- Endgame net worth from rounds is now 36000, equivalent to 3 T4 items and 3 T3 items or 1 T5 and 5 T2 items.

## Attribute Scaling
- Spell amplification from Intelligence removed. Instead increases base damage of spells additively, stacking with the Primary Attribute bonus.
- Increased bonus spell damage from Primary Attribute from 2% per 100 to 2.5% per 100. Universal Hero gain from 1% per 100 All Stats to 1.33%
- This means Intelligence heroes gain +4.5% increased spell damage from 100 Intelligence, Universal Heroes gain +3.33%, other Heroes gain the original +2%.
- Attack speed no longer scales diminishingly (previously was 25 attack speed for 100 agility, afterwards required 3.5x agility to double the attack speed). Heroes now gain 1 attack speed every 10 agility. Values at 100, 1000, 10000 agility from 25/67/181 to 10/100/1000
- Armor no longer scales diminishingly (previously was 0.6 armor every 10 agility, afterwards requiring 5x the agility to double the armor bonus). Heroes now gain 0.15 armor every 10 agility. Values at 100, 1000, 10000 agility from 6.5/17/47 to 1.5/15/150
- Magic resistance scaling changed from 4% magic resistance for 100 intelligence, then requiring 5x the intelligence to 2x the bonus. Instead, heroes gain 0.2% diminishing magic resistance every 10 intelligence. Each instance is treated as a seperate source of magic resistance (1 - 0.998^Intelligence/10). Still effectively provides 0.2% EHP against magic damage every 10 Intelligence. Values at 100, 1000, 10000 intelligence from 4/10.7/29% to 2/18/86.5%

## Restoration Amplification
- *2.0.0a.* Reworked entirely because Valve broke this for custom games.
-*2.0.0a.*  Removed 100% cap on Restoration Amp.
-*2.0.0a.*  Positive restoration amp and negative restoration amp add additively with restoration amplification of the same type. Negative and positive restoration amp multiply each other. Ex., 25+50% Restore Amp and -25% + -15% will add up to +75% restoration amplification and -40% Restoration Amplification. This then multiplies as 1.75 x 0.6 = 1.05 => for a total of +5% restoration amplification.
-*2.0.0a.*  More than -100% restoration amplification turns healing and restoration into health loss instead.
-*2.0.0a.*  All items that previously granted spell lifesteal, lifesteal, incoming healing or health regeneration amplification now grant Restoration Amplification.
-*2.0.0a.*  Strength now provides Restoration Amplification.

## Shop
- Reworked categories. There are now 8 categories.
- Vanguard: Items that focus around damage and debuff mitigation, counter-attacking and sustain.
- Assassin: Items that focus on single-target burst damage and high sustained damage.
- Speedster: Items that focus on mobility and evasion.
- Brawler: Items that focus on close-range, often AoE damage and fighting toe-to-toe with enemies.
- Evoker: Items that focus on spell damage and improving spells in various ways.
- Commander: Items that focus on supporting your allies and improving the team.
- Tactician: Items that focus on debuffing enemies and undoing their abilities.
- Other: Items that fit in cannot be defined by any other role.

<div align="center">
  <h1>Items</h1>
</div>

## Blood Gem
- Reworked active: "Crystallize Blood - For 8 seconds, this item Lifesteals from damage you take, instantly turning it into False Barrier"
- Duration and cooldown unchanged.

<div align="center">
  <h1>Heroes</h1>
</div>

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

## Bounty Hunter
- Removed DOTA 2 Aghanim's Shard and Scepter effects
- Replaced DOTA 2 facets with Expert Tracker and Takedown Specialist.
- Jinada: Gold steal can only proc once on each enemy. Hero reward increased from 12/20/28/36 to 24/40/56/72.
- Track: No longer grants bonus gold on kill. Track grants the following benefits: Target takes increased damage, Shuriken Toss bounces to all Tracked units, Jinada grants gold to all allies when Bounty Hunter gains gold from it against a Tracked unit, Shadow Walk stun duration is increased by 0.1/0.2/0.3s.

## Bounty Hunter - Expert Tracker
- Big Game Hunter: Neutrals killed by Bounty Hunter have a 10% reward increase.
- Shuriken Toss: Slow duration increased to 1/2/3/4 seconds and also decreased attack speed by 200.
- Jinada: Jinada randomly Silences, Disarms or Breaks units affected by Jinada for 3 seconds.
- Shadow Walk: Shadow Walk gains a sub-ability called Friendly Shadow, which can be cast on allies to grant the benefits of Shadow Walk to them.
- Track: Allied units lifesteal 10/20/30% against Tracked units and benefit from the bonus movement speed.
- Lv10 Talents: Shadow Walk 15% Damage Reduction / Silenced/Disarmed/Broken +50% Shuriken Toss Damage
- Lv15 Talents: +1 Jinada Status / Shadow Walk/Friendly Shadow 2 Charges
- Lv20 Talents: Track Bonus Attack Speed Equal To Movespeed / Shuriken Toss Root and Disarm
- Lv25 Talents: Tracked Units Suffer Jinada When Targeted / Shadow Walk 500 AOE Shuriken Toss

## Bounty Hunter: Takedown Specialist
- Big Game Hunter: Each Hero unit kill grants Bounty Hunter a stack of Headhunter. Big Game Hunter grants Bounty Hunter a 20% chance to deal 120% + 5% x Headhunter stacks critical damage. Tracked Heroes always grant Headhunter stacks even if Bounty Hunter didn't kill them.
- Shuriken Toss: Shuriken Toss splits into two Lesser Shurikens that each deal 50% of the damage to two random units.
- Jinada: Units affected by Jinada lose 0.5/0.75/1.0/1.25% of their maximum health every second for 3 seconds.
- Shadow Walk: Total stun duration is doubled and units have their armor reduced by 6 for the duration.
- Track: The incoming damage is increased to 16/24/32% for Bounty Hunter
- Lv10 Talents: Shadow Walk Armor Debuff Lingers 3s / +20% Lesser Shuriken Toss Damage
- Lv15 Talents: +50% Jinada Damage / Shadow Walk Gain And Guarantee Headhunter
- Lv20 Talents: +8/16% Track Damage Amp / Shuriken Toss +1 Split
- Lv25 Talents: Tracked Units No Jinada CD / Shadow Walk Refreshes All CDs

## Dark Seer
- Wall of Replica: Duration from 6/8/10 to 9/12/15
- Wall of Replica: Illusion damage no longer scales with Hero Power.

## Doom
- Lvl? Pain (Gluttony and Sloth): Current cooldown reduction from 25% to 15%
- Devour (Pride and Envy): Bonus armor increased from 3/4/5/6 to 6/9/12/15
- Devour (Pride and Envy): Bonus magic resistance increased from 8/10/12/14% to 12/15/18/21%
- Devour (Wrath and Greed): Bonus attack damage increased from 100/200/300/400 to 200/400/600/800
- Devour (Wrath and Greed): Cleave damage rescaled from 50% to 20/30/40/50%
- Devour (Gluttony and Sloth): Bonus mana regeneration increased from 3/6/9/12 to 6/10/14/18
- Scorched Earth: Damage per second increased from 200/350/500/650 to 400/700/1000/1300
- Scorched Earth: Bonus movement speed increased from 7/8/9/10% to 7/10/13/16%
- Scorched Earth: Duration rescaled from 10/12/14/16 to 16
- Scorched Earth: Cooldown rescaled from 41/39/37/35 to 35
- Scorched Earth (Pride and Envy): Incoming healing bonus increased from 7/8/9/10 to 7/9/11/13%
- Scorched Earth (Wrath and Greed): Bonus attack speed increased from 35/65/95/125 to 35/70/105/140
- Scorched Earth (Gluttony and Sloth): Attack speed slow increased from 40/50/60/70 to 40/60/80/100
- Infernal Blade: Cooldown reduced from 13/10/7/4 to 7/6/5/4
- Infernal Blade: Base damage increased from 200/300/400/500 to 400/600/800/1000
- Infernal Blade: Max health damage increased from 1/2/3/4% to 4%
- Infernal Blade: Stun duration reduced from 0.6 to 0.2
- Infernal Blade: Stun duration Talent bonus rescaled from +0.6 to +100%
- Infernal Blade (Pride and Envy): Now increases stun duration by 0.8s
- Infernal Blade (Pride and Envy): Now increases base damage by 50%
- Infernal Blade (Pride and Envy): Now increases max health damage by +4
- Infernal Blade (Gluttony and Sloth): Reduces cooldown to 4.5/3/1.5/0
- Doom: Cooldown reduced from 140/130/120 to 80/70/60
- Doom: Damage increased from 300/500/700 to 1200/1800/2400
- Doom (Gluttony and Sloth): Now reduces cooldown by 15.

## Enchantress
- Sproink: Attack targets increased from 3 to 4
- Impetus: Cooldown reduced from 6/4/2/0 to 2/1.25/0.75/0
- Impetus: Mana cost reduced from 50 to 35
- Impetus: Damage increased from 50/100/150/200 to 200/325/450/575%
- Impetus: Distance Damage Talent bonus from +50 to +25%

## Huskar
- Burning Spears: Burn damage from 50/100/150/200 to 75/150/

## Lich
- Frost Shield: Cooldown from 30/25/20/15 to 15
- Ice Spire: Cooldown from 25 to 20
- Chain Frost: Cooldown from 100/80/60 to 60
- Chain Frost: Total bounces from 10 to 10/15/20

## Lina
- Disabled

## Luna
- Lunar Blessing: Night multiplier reduced from 2 to 1.5
- Lunar Blessing: Self multiplier reduced from 2 to 1.5
- Lunar Blessing (Wrathbearer): Damage stacking duration reduced from 10 to 7
- Lunar Blessing (Spiteshield): Bonus armor increased from 1/2/3/4 to 2/4/6/8
- Lucent Beam (Spiteshield): Healing increased from 250/500/750/1000 to 500/1500/2500/3500 and now affects all allies.
- Lunar Orbit: Collision damage reduced from 22/28/34/40% to 16/20/24/28%
- Lunar Orbit (Wrathbearer): Rotation speed bonus from +50% to +25%
- Eclipse: Cooldown from 110 to 70 (from 70 to 50 with talent)
- Eclipse: Damage interval from 0.6 to 1.0 (from 0.4 to 0.5 for Wrathbearer)
- Eclipse (Spiteshield): Now increases night duration from +10 to +10/15/20

## Night Stalker
- Void (Void Bringer): Max level damage increased from 4000 to 5600
- Crippling Fear: Mana cost per second reduced from 90 to 50
- Crippling Fear: Mana cost per second (night) reduced from 60 to 25
- Crippling Fear: Cooldown reduced from 30/25/20/15 to 10
- Darkness: Duration increased from 30 to 60
- Darkness: Duration Talent bonus increased from +8 to +15
- Darkness: Bonus damage increased from 500/1000/1500 to 1000/2000/3000

## Nyx Assassin
- Impale (Libellumorph): Attack damage bonus increased from 200/300/400/500 to 600/900/1200/1500
- Impale (Aulacimorph): Damage per second per scarab from 40/80/120/160 to 120/240/360/480

## Outworld Destroyer
- Obnoxious Deconstructer: Increased bonus mana per intelligence from 0.1 to 0.5
- Arcane Orb cooldown from 6/4/2/0 to 3/2/1/0
- Essence Flux scepter barrier from 65% to 130%, scaling with hero power.
- Sanity's Eclipse cooldown from 150/135/120 to 80/70/60

## Phantom Assassin
- Immaterial: Stack loss delay from 1.5 to 3
- Stifling Dagger: Base damage increased from 650/700/750/800 to 650/900/1150/1400
- Stifling Dagger (Lanceuse): Additional strike damage multiplier increased from 50% to 150%
- Stifling Dagger (Femme Fatale): Stun duration increased from 1.0 to 1.5/2.0/2.5/3.0
- Stifling Dagger (Femme Fatale): Root duration increased from 2 to 3/4/5/6
- Phantom Strike (Femmet Fatale): Counterstrike bonus damage from 200/250/300/350 to 200/300/400/500
- Phantom Strike (Femmet Fatale): Counterstrike Damage Talent bonus from +100 to +200
- Coup de Grace: Critical damage from 200/300/400 to 300/375/450%
- Coup de Grace (Lanceuse): Break duration from 3 to 1/2/3
- Coup de Grace (Femme Fatale): Current health damage from 1.0/1.5/2.0% to 0.8/1.2/1.6%

## Phoenix
- Dying Light: Missing health to damage rescaled from 6% to 3%, but scales with hero power.
- Sun Ray: Max health heal from 0.5/1.0/1.5/2.0% to 2.5/4.0/5.5/7.0%
- Supernova: Cooldown reduced from 120/90/60 to 80/70/60

## Pudge
- Replaced all old talents.

## Pudge - Rotten Giant
- Lv10 Talents: Meat Hook Storm (Pudge launches a total of 8 hooks towards every direction) / Rot 2s Area Linger (Rot Aura lingers even after Pudge moves)
- Lv15 Talents: Meat Shield 50% Status Resistance / Meat Hook Debuff Lifesteals Pudge
- Lv20 Talents: Rot Fears 2s Delay/Duration / Dismember No-Target Feast (Dismember becomes a no-target instant-cast ability affecting all enemy units in range.
- Lv25 Talents: Dismember Bites Launch Hooks / Meat Shield Empowers Rot (Rot damage and radius is doubled while Meat Shield is active)

## Pudge - Flesh Carver
- Lv10 Talents: Meat Hook Debuff 0.5% Max HP Bleed / Improved Rot Control (Rot base damage increase rate doubled, base damage loss rate halved.)
- Lv15 Talents: Meat Shield 1.5s Invulnerability / Mobile Meat Hook (Pudge gains 20% increased phased movement speed, is no longer stunned while Hook extends and Meat Hook is 50% faster)
- Lv20 Talents: Rot Softens Up Enemies For Pudge (Enemies take additional physical damage when attacked by Pudge equal to the Rot damage) / Dismember Debuff Immunity
- Lv25 Talents: Dismember Damage Amp Aura / Meat Shield Colossus (Pudge gains +50% strength and size while Meat Shield is active)

## Razor
- Static Link: Cooldown reduced from 35/30/25/20 to 20.
- Static Link: Drain duration increased from 12/14/16/18 to 16/18/20/22

## Silencer
- Brain Drain: Permanent intelligence gain increased from 1 to 3
- Glaives of Wisdom: Intelligence gain duration increased from 15 to 15/20/25/30
- Glaives of Wisdom: Int Gain Duration Talent bonus increased from +15 to +20
- Global Silence: Cooldown reduced from 120 to 60
- Global Silence: Cooldown Talent bonus reduced from -20 to -15

## Slark
- Essence Shift: Permanent agility bonus from +1 to +4
- Essence Shift: Temporary agility duration from 20 to 15/20/25/30

## Spirit Breaker
- Herd Mentality: Movement speed bonus per unit increased from 4 to 8
- Herd Mentality: Unlocks Spirit Breaker's movement speed.
- Charge of Darkness: Cooldown reduced from 22/19/16/13 to 15/13/11/9
- Charge of Darkness (Bull Rush): Linger duration from 0.5 to 3.
- Bulldoze: Barrier from 1000/2000/3000/4000 to 2000/4000/6000/8000
- Nether Strike: Cooldown reduced from 75/55/35 to 25/20/15

## Tinker
- March of the Machines: Damage per robot from 170/260/350/440 to 350/500/650/800
- March of the Machines (Repair Bots): Heal per robot from 140/210/280/350 to 350/700/1050/1400

## Treant Protector
- Nature's Grasp: Cooldown reduced from 20/19/18/17 to 15
- Nature's Grasp: Damage per second increased from 300/400/500/600 to 600/800/1000/1200
- Leech Seed: Damage/heal from 150/300/450/600 to 250/500/750/1000
- Living Armor: Heal per second from 30/40/50/60 to 30/60/90/120
- Living Armor: Duration increased from 15/20/25/30 to 30
- Overgrowth: Duration increased from 3/4/5 to 4/6/8
- Overgrowth: Damage per second increased from 850 to 850/1250/1650
- Overgrowth: Cooldown reduced from 120/110/100 to 80/70/60
- Overgrowth: Cooldown Talent bonus reduced from -35 to -15

## Void Spirit
- Removed DOTA 2 Aghanim's Shard and Scepter effects
- Replaced DOTA 2 facets with Immortal and Incomprehensible.
- Replaced DOTA 2 talents. Each facet has unique talents.
- Intrinsic Edge: No longer grants 25% bonus health regen, armor, magic resistance and mana regeneration from strength, agility and intelligence. Instead, Void Spirit gains 6% increased attributes.
- Aether Remnant: No longer pulls enemies one at a time. Instead all units within the beam are Hypnotized by the Remnant, taking damage every 0.2 seconds until the max duration is reached. Total damage unchanged.
- Resonant Pulse: Buff duration no longer ticks down while Banished or Invulnerable.
- Astral Step: You can now detonate the Void Mark early by dealing damage with your abilities. When the Void Mark is detonated this way, the slow debuff is refreshed and its duration is increased by 60/100/140% (2/2.5/3 seconds, for a maximum total of up to 3.25/3.75/4.25 seconds). The Void Mark is applied before the attack's damage is dealt.

## Void Spirit - Immortal
- Intrinsic Edge: Void Spirit gains +4% increased strength.
- Aether Remnant: When an enemy is no longer Hypnotized by Aether Remnant, they take an additional 500/1000/1500/2000 damage and are stunned for the time they were Hypnotized.
- Dissimilate: Dissimilate Disarms enemies for 1.5/2/2.5/3 seconds upon phasing in.
- Resonant Pulse: Resonant Pulse grants Universal Barrier instead of Physical Barrier
- Astral Step: Astral Step's Void Mark mini-stuns when detonated and slows attack speed by 80/120/160.
- Lv10 talents are: Resonant Pulse 1.5s Silence / Dissimilate Phased 10% Max Health Regeration (You regenerate up to 10% of your maximum health while Phased Out)
- Lv15 talents are: Aether Remnant Cross-Watch (You send out 4 Aether Remnants, each being oriented orthoganally from the original.) / 2 Resonant Pulse Charges
- Lv20 talents are: 25% Astral Step Lifesteal / Dissimilate Stuns
- Lv25 talents are: Aether Remnants Dissimilate On Expire / Astral Step Activates Resonant Pulse

## Void Spirit - Incomprehensible
- Intrinsic Edge: Void Spirit gains +4% bonus agility and intelligence.
- Aether Remnant: Aether Remnants attack targets with bonus damage tick instead.
- Dissimilate: Dissimilate phase duration increased to 2/3/4/5, whenever you Phase Out, creates an Aether Remnant that lasts as long as you are Phased Out.
- Resonant Pulse: Resonant Pulse's cooldown is reduced by 6 each time you cast another spell.
- Astral Step: Void Mark debuff applies -2/4/6 armor.
- Lv10 talents are: Resonant Pulse Attacks Enemies / Additional Aether Remnants Created By Dissimilate
- Lv15 talents are: Aether Remnant 5s Target Reset (Enemies previously targeted by an Aether Remnant can be targeted again after 5 seconds) / +100 Attack Speed While Resonant Pulse Active
- Lv20 talents are: 140% Astral Step Crit / Dissimilate Outer Ring
- Lv25 talents are: First Aether Remnant Attack Applies Void Mark / Casting Astral Step Refreshes Dissimilate

## Zeus
- Static Field: Bonus spell damage increased from 200/400/600/800 to 300/600/900/1200
- Static Field: Bonus attack damage increased from 90/180/270/360 to 120/240/360/480
- Static Field (Epithet of Areios): Damage to barrier increased from 30% to 60%
- Arc Lightning (Aspect of Olympios): Bonus spell damage per stack increased from 9/10/11/12% to 9/12/15/18%.
- Thunderbolt: Ministun duration reduced from 0.35 to 0.15 
- Thunderbolt (Epithet of Brontaios): Bonus attack speed increased from 30/45/60/75 to 30/60/90/120
- Thunderbolt (Epithet of Olympios): Lightning Cloud damage increased from 15% to 25%
- Heavenly Jump: Damage targets increased from 1 to 3.
- Heavenly Jump: Cooldown reduced from 26/22/18/14 to 20/18/16/14
- Heavenly Jump (Epithet of Brontaios): Cooldown reduction increased from -2 to -4
- Thundergod's Wrath: Cooldown reduced from 120 to 90/80/70
- Thundergod's Wrath (Aspect of Areios): Damage to barrier from 75/80/85 to 75/100/125%

<div align="center">
  <h1>Bosses</h1>
</div>

## Enemy attributes
- All enemy units now have a 5% chance to deal 200% critical damage. Champions have a 20% chance instead.
- All enemy units now have 5% evasion. Champions have 20% evasion instead.

## Rage
- Reworked how Enraged works. Is no longer dispelled by dealing sufficient damage or a Hero dying.
- Enraged no longer increases enemy attack speed by 30% for each stack.
- Enraged damage amplification from 30% to 50%.
- Enraged movement speed bonus from 30% to 50%.
- Enraged stacks until flying movement increases from 5 to 3.
- Enraged reduces all forms of healing received by 25%, reduces armor by 3 and magic resistance by 10%.
- Enraged no longer triggers every 90/75/60/45 seconds of not being in combat for Normal/Hard/Impossible/Nightmare. Instead, it takes 120/110/100/90 seconds to become Enraged. Once a unit is Enraged, they gain a stack of Enraged every 60/50/40/30 seconds.
- Minions can no longer become Enraged