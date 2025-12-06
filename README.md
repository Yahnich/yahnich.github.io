> EBF 2.1.3 - 06/12/2025
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Burn
- Added a new mechanic to hero abilities and items, called Burn. Burn is handled by a primary non-stackable debuff.
- Burn stacks infinitely, dealing 50 magical damage for each stack every 0.25 seconds. Each time Burn deals damage, it loses 20% of its stacks.
- When a Burning unit is Dispelled, half of the Burn is removed.
- Burn has a default minimum value of 0, but some items increase this minimum, increasing the current stack appropriately. For example, an item that deals +25 Minimum Burn increases a unit's current and minimum burn by 25.
- Burn is shared among all heroes, stacks are removed chronologically. Damage dealt to a unit by Burn is based on the proportions of Burn applied. For example, a unit with 10 Burn, 2 applied by Batrider and 8 applied by Jakiro will take 1000 damage every 0.5 second, 200 of which will be attributed to Batrider and 800 of which will be attributed to Jakiro. Hero Power and Spell Amplification scales these accordingly.

## Poison
- Added a new mechanic to hero abilities and items, called Poison. Poison is handled by a primary debuff.
- Poison stacks infinitely, dealing 50 Pure damage for each stack every 3 seconds. This damage is considered health-loss and does not trigger on-damage effects.
- When a Poisoned unit is Dispelled, half of the Poison is removed. Any time a Poisoned Unit is healed, they lose 1 Poison for every 300 Healed and 2 Poison for every 300 Overhealed.
- Poison has a default minimum value of 0, but some items increase this minimum, increasing the current stack appropriately. For example, an item that deals +25 Minimum Poison increases a unit's current and minimum Poison by 25.
- Spell Amplification and Hero Power increases the amount of Poison applied and minimum Poison applied, rather than how much damage each stack deals.
- Poison is shared among all heroes, stacks are removed chronologically. Damage dealt to a unit by Poison is based on the proportions of Poison applied. For example, a unit with 10 Poison, 2 applied by Viper and 8 applied by Venomancer will take 3000 damage every 3 seconds, 600 of which will be attributed to Viper and 2400 of which will be attributed to Venomancer.

<div align="center">
  <h1>Items</h1>
</div>

## Fairy's Trinket
- Fae Escalation is now a Unique passive.

## Unhallowed Icon
- No longer heals the damaging unit, only the other Bloodbound units.
- Allied lifesteal from 2/4/6/8/10% to 6/7/8/9/10%
- Overheal sharing from 100% to 60/70/80/90/100%

<div align="center">
  <h1>Heroes</h1>
</div>

## Axe
- Blood Forged Axe: Damage amplification per stack from 1% to 1.5%.
- Blood Forged Axe: Stack duration from 3.5/5/6.5/8 to 8.
- Blood Forged Axe: No longer scales with Culling Blade.
- Blood Forged Axe (Berserker): Attack speed per stack from 8/10/12/14 to 2
- Blood Forged Axe (Skald): Healing and debuff duration amplification per stack from 0.75/1/1.25/1.5% to 1.5%.
- Battle Hunger (Skald): Base armor reduction increased from 2 to 4. Armor reduction per stack increased from 0.5 to 1.
- Counterhelix: Radius from 400 to 275
- Counterhelix (Jofurr): Now also increases radius to 400.
- Counterhelix (Berserker): Damage rescaled from 1000/1500/2000/2500 to 1200/1500/1800/2100
- Culling Blade: No longer restores Rage on Refresh.
- Culling Blade (Jofurr): Now also restores 40 Rage on Refresh.

## Bristleback
- Prickly: Current health threshold from 35% to 12%.
- Prickly (Boogerman): Now only fires one Viscous Nasal Goo towards the unit that triggered Prickly.
- Prickly  (Prick): Now only affects the triggering unit with Quill Spray. No longer considered reflection damage.
- Prickly (Mettlehead): Damage and debuff duration amp is always active, regardless of angle.
- Viscous Nasal Goo: Now deals 250 base damage + 50 per stack and can always be auto-cast. Auto-cast fires Goo on targeting Bristleback's attacker
- Viscous Nasal Goo (Prick): No longer automatically fires Nasal Goo when attacked. Base slip chance rescaled from 4/8/12/16% to 16%
- Viscous Nasal Goo (Mettlehead): No longer automatically fires Nasal Goo when attacking. Base attack damage reduction rescaled from 2/4/6/8 to 8%. Stack attack damage reduction increased from 1/2/3/4% to 3/4/5/6%
- Quill Spray (Boogerman): Debuff no longer increases physical damage taken. Instead applies a debuff increasing the strength of Viscous Nasal Goo's debuff values by 20/30/40/50% per stack. Debuff lasts 3 seconds.
- Quill Spray (Mettlehead): Adds a Strike trigger to Quill Spray: "When Bristleback hits an enemy unit, he gains a stacking buff that decreases Quill Spray's current cooldown by 0.1 second."
- Bristleback (Mettlehead): Rescaled Mettlehead's Bristleback damage reduction from 6/8/10/12% to 12%
- Warpath (Boogerman): No longer grants Goo bonus physical damage. Now increases debuff durations by 2/3/4% per stack without activating the ability. Activating Warpath grants Bristleback 20/30/40 Cast Speed.

## Faceless Void
- Time Lock is now his innate ability, granting him a 24% chance to Stun his attack target and attacking them again with bonus damage.
- Removed Distortion Field
- Time Dilation cooldown reduced to 16
- Chronosphere is now Faceless Void's third ability. Cooldown is 30/26/22/18. Duration is 2.0.
- Time Zone is now Faceless Void's ultimate ability.
- Deprecated Chronosphere and Time Zone facets. Replaced by Time Lord and Time Keeper.
- Time Lord increases Time Lock damage from 200 to 800 and increases all of Faceless Void's ability durations by 50%.
- Time Keeper reduces all of Faceless Void's cooldowns by 20%

## Huskar
- Removed Aghanim's Shard and Scepter effects.
- Removed DOTA 2 Facets.
- Uses Rage as a cast mechanic now.
- Blood Magic: Reworked and renamed into Burn Magic - Huskar can cast his abilities even without sufficient Rage, Burning himself for the Rage cost after Casting. Additionally, Huskar takes 50% Burn damage.
- Inner Fire: Removes all Burn from Huskar. Rage cost is 25.
- Burning Spear: Applies 6/7/8/9 Burn on Huskar and the target instead. No longer costs health.
- Berserker's Blood: Huskar cannot be killed by Burn damage.
- Life Break: The target gains Burn equal to the Burn on Huskar. Rage cost is 50.

## Huskar - Cauterizer
- Blood Magic: Huskar gains 0.5% spell amplification for each Burn applied to him.
- Inner Fire: Inner Fire deals 100/200/300/400 increased damage for each Burn removed from Huskar.
- Burning Spear: Burn increased to 7/9/11/13
- Berserker's Blood: Max magic resistance increased to 60/70/80/90%. Burn cannot reduce Huskar to less than 12% of his maximum health.
- Life Break: Units affected by Life Break's slow explode on death, spreading their remaining burn to all units within 600 units.

## Huskar - Fire-Hardened
- Blood Magic: Huskar gains 1% restoration amplification for each Burn applied to him.
- Inner Fire: Heals Huskar for the damage value, this healing is increased by 100/200/300/400 for each Burn removed.
- Burning Spear: Added Retribution trigger - Huskar deals 100 damage for each Burn applied to him to all units with 325 radius each time he is attacked. Has a 1 second internal cooldown.
- Berserker's Blood: Can be activated for 40 Rage with a 25/20/15/10 second cooldown. On activation, applies a Basic Dispel to Huskar and Huskar gains 100 health regeneration for each Burn on him for 3 seconds.
- Life Break: Huskar becomes immune to Burn damage and Burn does not tick down for the Debuff Immunity duration. The target is taunted to Huskar for the slow duration.

## Mars
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Dauntless: Reworked - Mars gains +40% Restoration Amp for each Hero within 700 range. Enemy Creeps grant +5%.
- Bulwark: While not toggled on, Mars can only benefit from the side reduction.
- Arena of Blood: Now also improves Mars' abilities: Spear of Mars is Replicated up to 1/2/3 times, firing out from a random Arena Soldier towards the nearest enemy unit. God's Rebuke is Replicated on every Arena Soldier. Mars is flanked by 5 Arena Soldiers while Bulwark is toggled on within the Arena.

## Mars - Epithet of Adamastos
- Dauntless: Mars gains 10% Spell and Attack Lifesteal.
- Spear of Mars: Spear of Mars now pins to the ground at the end of its range and the distance thrown can be chosen. Pinning the ground has the same behavior as pinning against a tree or another unit. Additionally, there is no upper maximum to the amount of units Skewered.
- God's Rebuke: Now has 50% lifesteal.
- Bulwark: When toggled, all enemies have a 70% chance to attack Mars if they weren't already and increases Front reduction by 10% and side reduction by 5%
- Arena of Blood: Mars gains 4% maximum health regeneration while in Arena of Blood.

## Mars - Epithet of Hoplochares
- Dauntless: Allies gain half the benefits of Dauntless and Dauntless grants 4 armor and 8% magic resistance for each Creep-Hero within range. Creeps grants 0.5 armor and 1% magic resistance.
- Spear of Mars: Leaves behind a trail of fire that slows enemy movement speed by 20/30/40/50% and deals 400/600/800/1000 damage per second.
- God's Rebuke: Slow duration increased from 2.5s to 6 seconds. Movement slow increased to 40/60/80/100% and reduces enemy attack slow by twice that amount.
- Bulwark: While toggled on, Bulwark becomes a 600 radius aura that grants allies the side reduction to any attack received.
- Arena of Blood: Damage resistance and amplification while within Arena of Mars increased to 16/20/24%

## Mars - Epithet of Vrotochtonos
- Dauntless: Mars gains bonus attack damage equal to its Restoration Amp.
- Spear of Mars: Damage increased by 50%
- God's Rebuke: Each time you are attacked by a Creep-Hero, the next God's Rebuke's critical damage is increased by 5%. Creeps increase this by 1%.
- Bulwark: Getting hit gives you a 100% attack boost for your next attack. The damage is reduced to 40% when getting hit from the front and 60% when getting hit from the sides. Highest buff has priority. Lingers for 0.8 seconds.
- Arena of Blood: Every second Mars stays in Arena of Mars, his attack speed increases by 10/20/30.

## Venomancer 
- Removed Aghanim's Shard and Scepter effects.
- Removed DOTA 2 Facets.
- Septic Shock: Venomancer deals bonus magic attack damage to Poisoned Units equal to 10x their Poison.
- Venomous Gale: Debuff no longer deals damage over time, Venomous Gale now applies 5/10/15/20 Poison immediately. Reapplying Venomous Gale purges the previous debuff.
- Poison Sting: Debuff no longer deals damage over time, the debuff now applies 1 Poison every second. Is now an Aura that affects all of Venomancer's summoned units, granting them Poison Sting's effects. Summons apply the debuff for half the duration.
- Noxious Plague: Reworked - No longer deals maximum health damage to the affected units. Instead, applies 5/7/9 Poison on impact and every second. Still slows enemy movement speed based on proximity to an infected unit. When Noxious Plague ends, the initial unit explodes, immediately taking their Poison damage and dealing it to all units within the aura. Units damaged by this are infected by a non-contagious version of Noxious Plague.
- Lv20 Left Talent from +150 All Stats to +100 Venomous Gale Impact Damage Per Poison

## Venomancer - Toxicologist
- Septic Shock: Every 4th attack, Venomancer Lifesteals for 50% of the damage dealt, sharing it with all allies within 900 radius.
- Venomous Gale: When Venomous Gale ends for any reason, the affected unit takes their Poison damage immediately and are stunned for 1.5/2/2.5/3.0 seconds
- Poison Sting: Poison Sting now also slows attack speed by an amount equal to the movement speed slow, additionally, movement speed and attack speed are slowed by +X%, where X is their Poison.
- Plague Ward: Plague Ward can be cast on allies, granting barrier equal to Plague Ward's health. Plague Ward is Invulnerable while attached to an allied unit, only dying when the barrier gained from Plague Ward is lost.
- Noxious Plague: When Noxious Plague ends, all allies in the radius are healed for the damage dealt.

## Venomancer - Plaguebringer
- Septic Shock: Every 4th attack, Septic Shock's damage is increased to 40x their Poison.
- Venomous Gale: The first time an enemy Hero is hit by Venomous Gale, create 1/2/3/4 Plague Wards.
- Poison Sting: Summoned units apply the full duration and if an enemy Champion dies while affected by Poison Sting, all of Venomancer's abilities are Refreshed.
- Plague Ward: Plague Wards explode on death, dealing 50% of their maximum health as physical damage.
- Noxious Plague: Noxious Plague can spread one additional time.

## Winter Wyvern
- Removed Aghanim's Shard and Aghanim's Scepter
- Replaced vanilla facets.
- Eldwyrm Scholar: Reworked, now grants Winter Wyvern +0.3% Spell Amplification per 100 Intelligence.
- Arctic Burn: Damage is now 200/400/600/800 damage per second. Deals an extra 4%/5%/6%/7% of the target's current HP every second. 
- Winter's Curse: Spell damage amplification from Wyvern reduced from 30% to 15%
- +700 Base Damage talent replaced with +100% Arctic Burn Base Damage Per Second

## Winter Wyvern - Glacierheart
- Eldwyrm Scholar: Winter Wyvern gains 0.4% Outgoing Heal Amp per 100 Intelligence
- Arctic Burn: Winter Wyvern releases a healing aura during the duration that heals allies for 4%/5%/6%/7% of their missing hp every second.
- Splinter Blast: When an ally is targeted by Splinter Blast's primary projectile, they benefit from 1.5 second Cold Embrace.
- Cold Embrace: Allies affected by Cold Embrace are not stunned. Refreshing the modifier increases the duration.
- Winter's Curse: All allied units benefit from the spell damage amplification and gain the bonus attack speed when attacking.

## Winter Wyvern - Blizzardborne
- Eldwyrm Scholar: Winter Wyvern gains 0.2% Debuff Duration Amp per 100 Intelligence
- Arctic Burn: Movement slow is increased to 100% at all levels and also slows attack speed by 60/80/100/120.
- Splinter Blast: Splinter Blast radius increased to 1000. Units hit by Splinter Blast's secondary projectile also take an additional 500/1000/1500/2000 damage when damaged while debuffed, this can only trigger once every second.
- Cold Embrace: Can target enemy units, lasting 50% of the duration, does not heal them, instead deals damage equal to the base healing per second. Does not turn the enemy immune to physical damage.
- Winter's Curse: Winter's Curse duration is increased for each affected unit and does not end if there are no attacking units.

## Winter Wyvern - Avalanchian
- Eldwyrm Scholar: Spell Amp gained increased to 0.5%.
- Arctic Burn: Becomes a toggleable ability, consuming 13/17/21/25 mana per second. Debuff can now be refreshed.
- Splinter Blast: Splinter Blast's primary target takes 150% of the secondary projectile's damage. If a unit dies while under Splinter Blast's debuff, they release secondary projectiles.
- Cold Embrace: Releases a Splinter Blast when the buff ends.
- Winter's Curse: Winter Wyvern gains double the bonus attack speed when attacking the Cursed unit and spell damage amplification increased to 30%.

<div align="center">
  <h1>Bosses</h1>
</div>

## Troll Warlord Round
- No longer has Switch Stance, Berserker's Blood or Berserker's Rage.
- Replaced Whirling Axes (Ranged) with Hurl Axe: "For each player, the Troll Warlord hurls an axe towards them that goes 900/1200/1500/1800 units forwards at 900/1200/1500/1800 speed. Units that collide with the Axe take minor spell damage and are slowed by 35/40/45/50% for 2.5 seconds."
- Replaced Whirling Axes (Melee) with Dance of Axes: "Troll Warlord creates two axes + 1 for each player beyond the first that orbit around him. Units that collide with an axe take minor spell damage and are blinded by 20/30/40/50%. The axes orbit outward, up to a distance of 600 units."
- Added Meteor Strike: "Troll Warlord leaps to targeted point, on impact he attacks all units in melee attack range (300 units). This attack deals 350/400/450/500% critical damage
- Fervor no longer creates an additional ranged attack thrown at a random unit in range.
- Added Flexible Warrior: When attacking a unit within 300 units of Troll Warlord, Troll Warlord gains bonus armor and magic resistance and a 16% chance to create one Dance of Axes axe. Whenattacking a unit beyond 300 units of Troll Warlord, he has a 16% chance to create a Hurl Axe axe. When not attacking any unit, Troll Warlord gains +15/18/21/24% bonus movement speed. Chances are increased by 2% for each stack of Fervor.
- Added Battle Trance: Troll Warlord Silences himself for 5.0/5.5/6.0/6.5 seconds. During this, he gains 140/170/200/230 bonus attack speed, 40/50/60/80% lifesteal and cannot Die.

