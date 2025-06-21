> EBF 2.0.0a - 11/06/2025
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

## Items
- Various neutral artifacts are now purchasable items. Their cost depends on their Tier, Tier 1 being basic and Tier 5 being Bahamut.
- All items and their recipes and costs have been drastically simplified. All base items now cost 1000g and require no components. You upgrade any item by combining two items of the same rarity.
- This means all basic items, such as Voodoo Mask, Claymore, etc have been removed.
- Attribute bonuses adapted to compensate. As a rule of thumb, every tier increase increases all passive bonuses by 75%, as if you had both items in your inventory slot, with a minor reduction for inventory efficiency. Auras and active effects scale linearly.
- Simplified item designs as follows:
- Removed Mask of Madness and its effects from Armlet upgrades
- Removed Battlefury and Talisman of Evasion and their effects from Sange and Yasha upgrades.
- Removed Battlefury, Talisman of Evasion and their effects from Sange and Yasha upgrades
- Removed Aeon Disk and Voodoo Mask and their effects from Kaya and Sange upgrades
- Removed Mask of Madness, Void's Reach and Mjollnir and their effects from Yasha and Kaya upgrades
- Removed Yasha and Morbid Mask from Butterfly upgrades.
- Removed Skadi and its effects from Radiance upgrades.
- Removed Shiva's Guard and Radiance and their effects from Eternal Shroud upgrades.
- Removed Shiva's Guard and its effects from Assault Cuirass upgrades.
- Removed cooldown reduction from Dagon upgrades.

## Neutral Items
- All current Artifacts and Enchantments have been removed. Renamed Neutral Artifacts and Enchantments to Role Artifacts and Enchantments. You get 5 Madstone to purchase your first at game start and have access to all artifacts and enchantments each time.
- Artifacts grant you PERMANENT bonuses. Switching Artifacts does not reset the bonuses gained. The bonuses scale retroactively with hero power where applicable (damage, health, bonus stats, etc)
- Added Artifact of Shields: Every 500 damage you take, gain 1 health.
- Added Artifact of Blades: Every time you attack, gain 1 damage.
- Added Artifact of Wands : Each time you Cast a Spell, gain 0.1% spell amplification.
- Added Artifact of Balance: You gain +1 all stats every 10 seconds.
- Added Deadly enchantment: Grants 15/20/25/30/35% bonus damage and 10/20/30/40/50 attack speed.
- Added Brawny enchantment: Grants 10/15/20/25/30% increased healing received and 10/12/14/16/18% bonus health.
- Added Mystical enchantment: Reduces ability costs by 10/15/20/25/30% and increases spell amplification by 15/25/35/45/55%.
- Added Tough enchantment: Grants 10/15/20/25/30% magic resistance and 4/6/8/10/12 armor.

## Ethereal Blade
- Removed status resistance and evasion bonuses.

## Spear of Justice
- Removed Hurricane Thrust active
- Removed attack range bonus, bonus health, bonus attack speed and bonus intelligence and bonus agility from the item
- Added bonus health regeneration and increased bonus damage.
- Buffed Echo Strike from 6/5/4/3/2 (9/8/7/6/5) to 5/4/3/2/1 (7/6/5/4)

## Hurricane Pike
- Hurricane Thrust now pulls melee heroes and their target closer together, instead of pushing them apart.
- Attack range bonus now work for melee heroes at half value (75/100/125/150/175).

## Signet of Destiny
- Removed bonus intelligence, agility and strength, removed bonus health, removed bonus armor
- Energy Burst no longer uses charges and no longer instantly heals or damages based on charges.

## Cloak of the Protector
- Removed bonus all stats, bonus health, bonus mana, bonus health regeneration (still exists in the aura)
- Whenever units affected by Aura of Protection lose more than 10% of their maximum health, this item's cooldown is reduced by 2/4/6/8/10

## Fallen Sky
- Removed mana regeneration amplification bonus, spell lifesteal amplification bonus and spell amplification bonus.

## Duelists Gloves
- Now grants an additional 10/20/30/40/50% bonus for each additional Hero within range.

## Specialist's Array
- Now works for melee heroes as well, attack range bonus for additional target is halved.

## Iron Talon
- Added Passive effect: Ruthless - When you kill a unit, a random ability has its cooldown reduced by 0.5/1/1.5/2 seconds. This is increased to 4/6/8/10 seconds when killing a Hero.

## Cloak of Flames
- Reworked Immolate: When you are attacked, all enemies with 375 radius of you take 450/900/1350/1800/2250 damage every second for 2 seconds. Does not stack.

## Vindicator's Axe
- Reworked Vengeance: Now gives the damage bonus when debuffed, grants the armor bonus when Attack Disabled (Disarm, Stun, Fear, etc...)

## Occult Bracelet
- Rites of Eloshar: Now also increases the damage dealt to units within 500 units of you by 2/2.5/3/3.5/4% per stack

## Nexus of Vigor
- New Vanguard item.
- Grants 5/8.75/15.25/26.5/47% incoming healing amplification and 20/35/60/105/185 strength.
- Passive effect: Vital Surge - When you are Overhealed, you deal 25/40/65/80/95% of the excess healing as damage to all enemies within 375 radius.## Nexus of Vigor
- *2.0.0a.* Nexus of Vigor now deals Pure damage equal to the amount Healed (rather than Overhealed) equal to 60/70/80/90/100%
- *2.0.0a.* Overhealing increases the damage dealt by 30/35/40/45/50% (total damage equal to 78/94.5/112/130.5/150%)
- *2.0.0a.* Nexus of Vigor now uses Restoration Amplification instead of Incoming Healing Amplification (affects health regeneration, lifesteal and spell lifesteal as well, although these do not interact with its passive)

## Drum of Chorus
- New Commander item
- Grants 5/8.75/15.25/26.5/47% spell amplification and 10/18/31/54/94 Primary attribute.
- Each time another allied unit within 900 units of you Casts a Basic Spell, you gain 10/15/20/25/30% bonus movement speed and your Spells cooldown 10/15/20/25/30% faster for 5 seconds. If no other unit is within 900 radius, triggers on self and if you are already affected by this bonus, another random allied unit in radius gains the buff.

# Assassin's Dagger
- New Assassin item
- Grants 20/35/61/107/188 attack speed.
- Active effect (15/14/13/12/11/10 CD): Assassin's Gambit - You Blink towards the targeted location up to 1200 units away, the first attack made within 3 seconds is a guaranteed critical hit that deals 200/250/300/350/450% critical damage.
- Passive effect: Blood Revelery - When you critically hit, you gain 25/50/75/100/125 bonus attack speed and 5/10/15/20/25% attack lifesteal for 3 seconds.
## Archmage's Naginata
- New Evoker item
- Grants mana regeneration, attack damage and intelligence.
- Passive effect: Spellblade - Your attacks have an 18% chance to reduce all current cooldowns by 1/2/3/4/5%.

## Lunar Sigil
- New Evoker item
- Places a debuff on a unit, doubles all spell damage they receive, up to a maximum of 1500/3000/4500/6000/7500.

## Refresher Orb
- Reworked Evoker item
- Active ability cooldown from 185 to 185/165/145/125/105
- New passive effect: Refreshing - You r 100/200/300/400/500 health and 10/20/30/40/50 mana whenever you Cast a Spell

## Unhallowed Icon
- New Commander item
- Passive aura: Bloodbond Aura - All Allies within the 1200 AoE are Bloodbound. 2/4/6/8/10% of all damage dealt by a Bloodbound unit and any amount of healing over their current health maximum is distributed amongst all other Bloodbound units.

## Glimmer Cape
- Returning Commander Item
- Reworked Active: Glimmer - 10% of the Spell Damage absorbed by the barrier is converted into mana.

## Lucky Femur
- New Evoker item
- When you cast an ability, it has a 15/20/25/30/35% to be immediately refreshed, but you receive a debuff that increases its mana cost by 10% for each second of its cooldown. Debuff strength reduces linearly over time and stacks independently each time its triggered.
- *2.0.0a.* Bonus mana from 450/785/1375/2405/4210 to 250/438/767/1340/2345
- *2.0.0a.* Bonus intelligence replaced with bonus strength at the same values.
- *2.0.0a.* Instant refresh chance from 20/25/30/35/40% to 15/24.5/38.3/56/74.5%
- *2.0.0a.* Mana cost penalty changed from 10% per second of cooldown refreshed to 100% + 5% per second of cooldown refreshed. Still ticks down over time.
- *2.0.0a.* Modifier is now a buff, meaning it no longer interacts with debuff immunity

## Wand of Brine
- New Commander Item
- Active effect: Brinefoam - Turns the target invulnerable, stunned and hidden for 3 seconds. They Heal 500/1000/1500/2000/2500 every second.

## Soul Ring
- New Commander item
- Toggle effect: Consumption - You lose 10% of your maximum health every second. For every 1000 health lost this way, you and all allies within 1200 units regain 1/2/3/4/5 mana.

## Angelic Crown
- New Commander item
- Passive effect: Bless - Buffs you apply last 10/15/20/25/30% longer.

## Samaritan's Cloak
- New Commander Item
- Passive effect: Share the Spoils - When a buff is applied to you, another allied unit within 1200 units of you that does not already have it, gains that buff with a 40/50/60/70/80% duration.

## Watcher's Gaze
- New Tactician item.
- Active effect (45s cd): Enemies within your frontal cone are turned to stone and take 12/18/24/30/36% additional physical damage for 4 seconds.

## Sea-Cursed Trident
- New Tactician item.
- Passive effect: Creatures debuffed by you are Cursed, taking 4/6/8/10/12% additional damage from all sources.

<div align="center">
  <h1>Heroes</h1>
</div>

## Anti-Mage
- Removed Aghanim's Shard and Aghanim's Scepter
- Replaced vanilla facets.
- Persecutor innate reworked: Any time any unit within 900 units of Anti-Mage, including Anti-Mage, expends mana, the next instance of damage dealt by Anti-Mage has its damage increased by 150/200/250/300% of the mana spent as magical spell damage. Scales with ability power and Mana Void. Becomes Pure damage against units with less than 25% of their maximum mana.
- Mana Burn reworked into Mana Feedback: For 4 seconds, increases the mana cost of spells cast by 20/40/60/80 and upon Casting a Spell, slows the enemy by up to 40/60/80/100% for 4 seconds, scaling linearly with missing mana percentage.
- Counterspell reworked: Reduces spell damage of any damage type. Does not affect attack damage. No longer passively provides magic resistance. Cooldown from 8 to 3, no longer stacks with itself and no longer degrades. Recasting removes the previous Counterspell
- Mana Void: Does not consume Persecutor's stored damage when applying its damage.

## Ascetic's Path
- Persecutor: Anti-Mage gains a stacking barrier with no duration against all damage types and categories equal to the mana spent, up to 50% of his maximum health.
- Mana Burn: Initial debuff also reduces enemy outgoing spell damage by 15/20/25/30%.
- Blink: Restores 6/9/12/15% of your maximum health.
- Counterspell: When an enemy damages Counterspell's barrier, they take damage equal to the barrier lost of the same damage type.
- Mana Void: Expends 30% of the enemy and all of its allied units in range's maximum mana before calculating damage dealt.

## Pragmatic's Path
- Persecutor: Persecutor's base damage from 0 to 100/200/300/400 and becomes Pure damage against units with less than 50% of their maximum mana.
- Mana Burn: Initial debuff also causes units to take 8/10/12/14% more spell damage.
- Blink: Blinking causes an Illusion to appear where Anti-Mage was that deals 0/20/40/60% damage and takes 300/250/200/150% damage. Can be alt-cast to instead blink the Illusion to the location and not move Anti-Mage.
- Counterspell: After Counterspell ends, whether that is through expiring or taking damage, Anti-Mage gains a 60/80/100/120 attack speed bonus for 4 seconds and 10% of the total barrier is added to Persecutor's damage stored.
- Mana Void: Damage is increased by Anti-Mage's remaining mana, using the same multiplier as the targeted unit's missing mana.

### Bristleback
- Removed DOTA2 Aghanim's Scepter+Shard and Facets.
- Moved Bristleback's passive cast trigger to Prickly.
- Snot base armor reduction from 2/2/3/3 to 2/3/4/5.
- Snot armor reduction per stack from 1.5/2.0/2.5/3.0 to 1.0. The first stack no longer applies this bonus.
- Quill Spray no longer applies a debuff that increases the damage dealt by Quill Spray.
- Bristleback no longer releases a Quill Spray when hurt by default.
- Bristleback can now be activated by default. Has a 24 second cooldown.
- Warpath can now be activated by default, has a 60/50/40 second cooldown and increases War Path's bonuses by 50% for 10 seconds.
- War Path attack damage bonus from 150/200/250 to 150.
- *2.0.0a.* War Path: Attack damage bonus increased from 150 to 150/200/250
-*2.0.0a.* War Path: No longer gains stacks from Prickly passive casts (Mettlehead still gains a stack)

### Bristleback - Boogerman
- Prickly: After taking enough damage, casts Viscous Nasal Goo.
- Viscous Nasal Goo: Affects all units in a 500 AoE, max stacks increased to 8.
- Quill Spray: Applies an independently stacking debuff that lasts 14 seconds. Each stack increases the physical damage taken by that unit by 20/40/60/80. Damage dealt by Bristleback is increased by double the bonus.
- Bristleback: When activated manually, sends out a spiky glob of snot to the targeted location and releases 2/3/4/5 Viscous Nasal Goos and 1/1/2/2 Quill Sprays.
- War Path: Every stack of War Path causes Viscous Nasal Goo to deal 50/100/150 Physical spell damage. When activated, Bristleback gains 40/70/100 cast speed.
-*2.0.0a.* War Path: War Path stacks Viscous Nasal Good damage per stack from 50/100/150 to 40/60/80.
-*2.0.0a.* War Path: Activating War Path no longer grants cast speed. Instead grants 15/30/45% debuff duration increase.

### Bristleback - Prick
- Prickly: After taking enough damage, casts Quill Spray.
- Viscous Nasal Goo: Every 5th time you are attacked, a Viscous Nasal Goo is automatically launched to your attacker.
- Quill Spray: Base damage increased to 750/1500/2250/3000.
- Bristleback: When activated manually, turns Bristleback's back to the targeted location and sprays 3/4/5/6 conical Quill Sprays. Bristleback is slowed and Disarmed for the duration.
- War Path: Every stack of War Path grants 4/8/12% spell amplification. When activated, Bristleback gains 4/8/12% spell lifesteal.
-*2.0.0a.* Viscous Nasal Goo: Units affected by Goo have a 4/8/12/16% chance to slip and become disarmed for 0.4 seconds. Duration increases by 0.1/0.2/0.3/0.4 seconds per stack.

### Bristleback - Mettlehead
- Prickly: After taking enough damage, Bristleback gains a stack of Warpath.
- Viscous Nasal Goo: Every 5th time you attack, a Viscous Nasal Goo is automatically launched to your target.
- Quill Spray: Enemies damaged by Quill Spray receive a stacking debuff with independent durations. When Bristleback attacks a unit affected by Quill Spray's debuff, all the stacks are consumed to deal 100/200/300/400 additional physical damage per stack.
- Bristleback: When activated manually, Bristleback's minimum and maximum damage reduction is increased by 4/8/12/16%
- War Path: Also grants 10/15/20/25 attack speed per stack. When activated, Bristleback gains 20/30/40% lifesteal.
-*2.0.0a.* Viscous Nasal Goo: Units affected by Goo deal 2/4/6/8% less attack damage, increases by 1/2/3/4% for each stack.
-*2.0.0a.* War Path: Maximum stacks increased from 8/10/12 to 10/14/18.

### Centaur
- Removed Aghanim's Scepter and Shard effects.
- Removed all DOTA 2 facets.
- Replaced Retaliate Aura with +100% Stampede damage.

### Centaur - Chieftain
- Centaur's Heart: Health per strength increased from 5 to 10.
- Hoof Stomp: Grants all allied units within 900 radius 30/50/70/90 attack speed for 5 seconds.
- Double Edge: Increases Centaur's Strength by 2/4/6/8% for each unit hit with Double Edge. Stack durations are independent.
- Retaliate: Retaliate is a 300/600/900/1200 radius aura that affects all allied Heroes.
- Stampede: Stampeding units gain 25% damage resistance.

### Centaur - Thunderhoof
- Centaur's Heart: Centaur has no movement speed cap, cannot be slowed and gains 2 base movement speed for each 100 Strength he has.
- Hoof Stomp: Slows affected enemies' attack speed by 60/100/140/180 for 5 seconds.
- Double Edge: Allies within 900 radius of Centaur Lifesteal for 70/80/90/100% of the damage taken by Centaur and 20/40/60/80% of the damage dealt to enemy units.
- Retaliate: Retaliate automatically activates on a random enemy unit within Centaur's attack range + 150 every 3.0/2.5/2.0/1.5 seconds. Additionally, units that take Retaliate damage have their attack damage reduced by 20% for 3 seconds.
- Stampede: Slow duration increased to 4 seconds and units Slowed by Stampede are Disarmed and Silenced. Stampeding units gain unobstructed movement.

### Centaur - Stepperazer
- Centaur's Heart: Centaur gains 1.5 bonus base damage per Strength.
- Hoof Stomp: Centaur is no longer Disarmed and has 50% damage resistance during Hoof Stomp.
- Double Edge: Each time Centaur is damaged, the damage dealt by Double-Edge is increased by the 1/2/3/4x percentage of health he lost, up to a maximum of +80% bonus damage. Centaur does not take this bonus damage.
- Retaliate: Centaur deals 50% of Retaliate's damage to each creature that attacked him in the last 2/3/4/5 seconds within his attack range + 150 each time he attacks.
- Stampede: Gains the Work Horse sub-ability, which grants Centaur the effects of Stampede and has a 40/35/30 second cooldown. Stampede damage increased from 2000/3000/4000 to 2500/5000/7500.

### Magnus
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Intelligence base and gain to 90/6.7.
- Solid Core: Magnus is immune to being slowed and has 25% status resistance.
- Empower: No longer grants increased bonuses to Magnus.
- Skewer is no longer the default ability.

### Magnus - Avenger
- Magnus is a Universal hero.
- Strength base and gain to 90/6.7, Agility base and gain to 90/6.7.
- Solid Core: Magnus gains 1% bonus attack damage for each point of Armor he has.
- Shockwave: Shockwave returns to Magnus's location upon reaching the maximum length, hitting enemies a second time for 75% of the damage.
- Empower: Permanent and more powerful on Magnus. Each attack provides a stacking bonus to damage and cleave of 2.5%, up to a max of 8/12/16/20 stacks. Stacks are refreshed on hit, and last 5 seconds.
- Gains Skewer: Magnus runs through all enemy units, attacking them once with bonus damage based on how far he has traveled.
- Reverse Polarity: Magnus gains 5/10/15 armor and 30/60/90 attack speed for 15 seconds.

### Magnus - Guardian
- Magnus is a Strength hero.
- Strength base and gain to 115/7.7, Agility base and gain to 65/5.7.
- Solid Core: Magnus gains 4 armor, increasing by 0.5 each level. Status resistance increases by 1% each level.
- Shockwave: Shockwave Disarms enemies during the slow duration and the slow duration is increased to 1.4 seconds.
- Empower: On cast, applies to all units within 800 units of Magnus.
- Gains Horn Toss: Tosses all enemies in front of Magnus into the air for 0.6. Upon landing, they take 1500/3000/4500/6000 damage and are stunned for 1.75s.
- Reverse Polarity: Affected units lose 5/10/15 armor and 30/60/90 attack speed for 15 seconds.  Can be alt-cast to push enemies away instead of pulling them in.

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