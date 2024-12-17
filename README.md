> EBF 1.5.3e - 14/10/2024
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Event - Roguelite
- Added Roguelite map. Heroes don't receive any gold (including starting gold), instead heroes receive 2 items of an appropriate tier every round.
- Neutrals don't have a bounty.
- Bottle removed, instead each hero starts with an Aegis of the Immortal.
- Round 1-5 drop Tier 1 items (Base).
- Round 6-11 drop Tier 2 items (Blue).
- Round 12-18 drop Tier 3 items (Red).
- Round 19-24 drop Tier 4 items (Gold).
- You can sell these items for half their shop value and buy items from the shop still.
- Heroes are randomized for every player, like Single Draft. The same hero can be available multiple times.
- There are only 25 rounds available. Bosses are split into pools. This means the order of bosses is random every game. The next 5 rounds are displayed on the UI.
- **1.5.3a:** Item drops are no longer limited by round, you can obtain a Tier 5 (Bahamut) item round 1.
- **1.5.3a:** This is weighted, the higher the round number, the higher the chances are of you obtaining a high-level item
- **1.5.3a:** Item chances are 80/10/5/3.5/1.5% for Tier 1/2/3/4/5 items at round 1. Every round reduces the Tier 1 item chance by 8%, granting 4.0/2/1.25/0.75% to the other tiers.
- **1.5.3a:** Tier 1 chance is 0% after round 10, after which the item chances are 0/50/25/16/9%. Each round after this reduces the Tier 2 chance by 5% and increases the chances of the other items by 2.5/1.5/1%; reaching a maximum after round 20 of 0/0/50/31/19%.
- **1.5.3a:** Added 1 additional Tier 4 round (pool consists of asura, doom, necrophos, etc), meaning there are now 25 instead of 24 rounds
- **1.5.3a:** Selling dropped items no longer grants gold. You can still sell items you bought yourself and dropped items you've upgraded as normal.
- **1.5.3a:** Heroes start with Aghanim's Shard and Scepter upgrades

## Ability Scaling
- **1.5.3b:** Hero initial base damage now scales with hero power, mostly affects earlygame attack damage output.
- **1.5.3b:** Ability power renamed to Hero Power now that it affects more things
- **1.5.3b:** Ability power scaling from +30% per level to +20%.
- **1.5.3b:** +35% Base Attributes talent changed to +1% Hero Power/Level
- **1.5.3b:** You no longer get free skill points level 17, 18 and 19
- **1.5.3b:** Reworked ability levels. All abilities now have the standard vanilla amount of levels. Basic abilities have 4 levels, ultimate abilities have 3.
- **1.5.3b:** Cooldowns and durations are reverted to vanilla scaling
- **1.5.3b:** Removed spell amplification scaling from primary attributes. You still gain provides 0.2% spell amplification per 10 Intelligence.
- **1.5.3b:** Primary attribute now directly increases the base damage of your spells, similar to ability power. Only affects spell damage, all other values are unaffected. Spell damage increase is 0.2% per 10 Primary. Multiplicative with ability power.
- **1.5.3b:** Ex (Lv13 Lina, 520 Intelligence). Level 7 Dragon Slave: 18840 damage (360% ability power x 20.8% spell amplification) / Level 4 Dragon Slave: 7661 damage (240% ability power x 7.5% spell amplification x 7.5% base spell damage)
- **1.5.3b:** Ex (Lv30 Lina, 6245 Intelligence). Level 7 Dragon Slave: 115025 damage (870% ability power x 249.8% spell amplification) / Level 4 Dragon Slave: 146361 damage (870% ability power x 124.9% spell amplification x 124.9%)
- **1.5.3b:** Overall damage values are weaker earlygame (the example does not include stats from items), but can peak higher lategame. Spell amplification items have more impact.

## Max HP Abilities
- **1.5.3c:** Returned to DOTA2 values.

<div align="center">
  <h1>Items</h1>
</div>

<div align="center">
  <h1>Heroes</h1>
</div>

## Gyrocopter
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Flak Cannon is no longer a default ability.
- Chop Shop innate replaced by Side Gunner: Every 1.8/1.6/1.4/1.2 seconds, Gyro auto-attacks a random unit in range. Scales with Call Down.

## Gyrocopter - Heavy Ordnance
- Side Gunner: The Side Gunner attack explodes, dealing 150/450/750/1050 magical damage to all units within 450 radius of the target, including the target.
- Rocket Barrage: Rocket Barrage damage increased by 40 and radius increased by 200.
- Homing Missile: Homing Missiles fire the current level of Rocket Barrage while moving.
- Flight of the Valkyrie: Replaces Flak Cannon - Gyrocopter gains increased Flying Movement and cannot stop moving forward, turn speed decreased. While active, Gyrocopter gains 10/20/30/40% bonus spell amplification Rocket Barrage and Homing Missile target all units in radius and Call Down becomes a No-Target ability, instead launching the missiles 500 units behind Gyrocopter for as long as Flight of the Valkyrie is active. Lasts 8 seconds.
- Call Down: Call Down creates delayed secondary explosions that deal 50% damage on Heroes hit.
- **1.5.3d:** Call Down's strike count is no longer infinite during Flight of the Valkyrie, instead increased up to its duration. (+5 baseline, +8 with talent)
- **1.5.3d:** Recasting Call Down during Flight of Valkyrie no longer creates a second, simultaneous Call Down, instead increases the current active effect's strike count accordingly.

## Gyrocopter - Assault Copter
- Side Gunner: Side Gunner's cooldown is reduced by 0.1 each time Gyrocopter attacks.
- Rocket Barrage: No longer deals Magical damage. Instead performs 25% damage auto-attacks with bonus damage that proc can effects. Every rocket that hits increases Gyrocopter's movement speed by 1/2/3/4% for 4 seconds.
- Homing Missile: Homing Missile no longer has a wind-up time and units hit by it have their armor reduced by 6 for 1.5/3/4.5/6 seconds.
- Flak Cannon: Flak Cannon no longer has a maximum attack count. Instead lasts 8 seconds and affects all attacks, including Side Gunner.
- Call Down: Base damage is increased by your attack damage.

## Kez
- Added

## Mirana
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Selemene's Faithful: After using an ability, Mirana gains +10% Base Attributes for 10 seconds. Stacks independently

## Mirana - New Moon
- Selemene's Faithful: Grants the attributes gained by Mirana to all allied Heroes.
- Starstorm: Each time a unit is affected by Starstorm, it takes 5% increased damage from all sources. Debuff lasts 8 seconds, stacks independently.
- Sacred Arrow: Sacred Arrow releases a Starstorm along the travel path.
- Leap: Upon landing, launches a projectile along Sagan's leap path, dealing damage and slowing units.
- Moonlight Shadow: As before.

## Mirana - Full Moon
- Selemene's Faithful: Additionally increases base attack speed by 10%.
- Starstorm: Units affected by Starstorm grant Mirana 12% lifesteal from all sources per stack of Starstorm. Debuff lasts 8 seconds, stacks independently.
- Sacred Arrow: Sacred Arrow always deals its maximum damage, regardless of distance. After casting Sacred Arrow, Mirana's next attack has a guaranteed chance to deal 200/250/300/350/400/450/500% critical damage.
- Leap: Gains one additional charge and attack speed buff duration increased to 8 seconds. Attack speed bonus increased by 25 at all levels.
- Moonlight Shadow: Increases attack speed and base attack damage by 10/15/20/25/30/35% every second, reaching maximum power after 8s. Allies receive 50% of the bonus

## Nature's Prophet
- Removed Aghanim's Scepter and Aghanim's Shard upgrades.
- Teleportation can be alt-cast, when alt-cast Treants teleport with Furion.
- Nature's Call scales properly with Ability Power.

## Nature's Prophet - Naturopath
- Spirit of the Forest: Nature's Prophet gains 5% Outgoing Heal Amp for each tree in addition.
- Sprout: Sprout heals allies in the radius for 200/300/400/500/600/700/800 health per second.
- Teleportation: Upon teleporting, creates a flower that emits gas for 5 seconds where Nature's Prophet left. Flower deals 100/200/300/400/500/600/700 damage per second to enemies within 450 radius. Nature's Prophet grants the Barrier to all Heroes within 450 units around the teleportation position.
- Nature's Call: Nature's Call Treants are Uncontrollable. They walk to the nearest ally not already targeted by another Treant and shoot healing pulses to that ally every 3 seconds. Each pulse heals for 300/600/900/1200/1500/1800/2100 health.
- Wrath of Nature: Wrath of Nature entangles all units hit for 2 seconds, each additional bounce increases the duration by 10%.

## Nature's Prophet - Arboriculturist
- Spirit of the Forest: Adds a 1200 radius aura that deals 100 damage per tree or Treant within 300 radius of an enemy unit.
- Sprout: Spawns two Treants instead of a Tree.
- Teleportation: All Treants gain the Barrier.
- Nature's Call: Treant base health is increased to 800/1050/1300/1550/1800/2050/2300 and base damage is increased to 160/240/320/400/480/560/640
- Wrath of Nature: Each time Wrath of Nature strikes an enemy, Furion and all Treants gain a 5% damage increase.

## Nature's Prophet - Phytomercenary
- Spirit of the Forest: Nature's Prophet gains 1 armor for each tree in addition.
- Sprout: Units within or near the trees have a 20/25/30/35/40/45/50% chance to miss.
- Teleportation: Barrier gained increased.
- Nature's Call: Nature's Prophet covers himself with Treants that each increase his health by 550 and damage by 85/135/185/235/285/335/385 for 50 seconds. Every 10% maximum health Nature's Prophet loses, a Treant dies.
- Wrath of Nature: Cooldown reduced by 25 seconds and destroys all trees within 450 units of Nature's Prophet. Adds a bounce for destroyed tree on the map.

## Nyx Assassin
- Removed Aghanim's Shard and Aghanim's Scepter
- Replaced vanilla facets.
- Nyxth Sense: Nyx's vision lingers for 2 seconds, as well as giving him the invisibility detection.
- Mana Burn replaced by Mind Flare. Deals 750/1000/1250/1500/1750/2000/2250 magical damage.
- Spiked Carapace no longer gives armor.
- No longer has a default Ultimate ability.
- +80 Agility talent replaced with a talent buffing Nyx Assassin's Ultimate Ability.

## Myrmeleomorph
- Nyxth Sense: Enemies within Nyx's detection radius take 10% increased damage from his abilities.
- Impale: Impale afflicts enemies with a debuff for 6 seconds that causes Nyx Asssassin to take 25% less damage from them.
- Mind Flare: Damage dealt is increased by 25% of the damage taken before reductions by Nyx Assassin from the target.
- Spiked Carapace: While Spiked Carapace is active, deals 20% of the Spiked Carapace damage to units within 250 units of Nyx Assassin every 0.5 seconds, without stunning them. Increases while Burrowed.
- Burrow: As it exists currently, but provides 7/11/15/19/23/27 armor and doubles Nyxth Sense radius and Nyx Assassin's vision radius. Bonuses scale with level now.
- Talents: Vendetta Damage talent becomes -0.75 Burrow Cast Time. Lv 25 talent is Burrow 2s Invisibility Delay.

## Libellumorph
- Nyxth Sense: Nyx Assassin gains 25% evasion and 25% magic resistance against units in the detection radius.
- Impale: Impale afflicts enemies with a 6s debuff that causes them to take 200/300/400/500 bonus damage from Nyx Assassin's abilities and attacks.
- Mind Flare: Damage dealt is increased by 25% of the damage taken before reductions by the target from Nyx Assassin.
- Spiked Carapace: Spiked Carapace's duration increased by 0.5 seconds and the same target can be affected by Spiked Carapace any number of times.
- Vendetta: As it currently exists, but Nyx gains flying movement.
- Talents: Lv 25 talent is Vendetta Debuff Breaks and Silences

## Aulacimorph
- Nyxth Sense: Damage dealt by Nyx's abilities to units within the detection radius drains 3% of the target's current mana and grants it to Nyx Assassin.
- Impale: Units hit by Impale are infested for 12s, taking 40/60/80/100/120/140/160 damage every second, stacking independently. If the unit dies, the swarm move towards a random enemy unit within 900 units. Reinfesting resets the scarab's lifetime.
- Mind Flare: Base damage increased by 100% and resets the duration of all debuffs and stacks applied by Nyx Assassin.
- Spiked Carapace: While Spiked Carapace is active, any time Nyx Assassin gains or loses mana, he gains Barrier equal to 2x the Mana Spent (scales with ability power).
- Parasitize: Nyx Assassin burrows into the target unit for 8/10/12 seconds. The unit changes to Nyx's team for the duration. While Parasitizing, Nyx Assassin's abilities consume the affected unit's mana instead of Nyx Assassin, unless they have no mana remaining. Additionally, Nyx Assassin's abilities always affect the target as if they were a targeted enemy, or as if they had triggered an ability. 80/70/60s CD
- Talents: Vendetta Damage talent becomes +2s Parasitize Duration, Lv 25 talent is Parasitize Grants Control of Unit

## Riki
- Innate changed from Backstab to Cloak and Dagger, reworked as follows: Riki goes invisible after 4 seconds. The first attack made while invisible is a Backstab and deals double damage.
- Backstab is still a basic ability.

## Shadow Fiend
- Shadowraze damage reduced from 900/1600/2300/3000/3700/4400/5100 to 500/1000/1500/2000/2500/3000/3500

## Shadow Fiend - The Ego
- Ego debuff is no longer applied by the secondary bursts.
- Ego debuff reworked from an armor debuff to 150/200/250/300/350/400/450 additional physical damage taken when attacked.
- Ego bonus damage per soul from 15/30/45/60/75/90/105 to 5/10/15/20/25/30/35

## Shadow Fiend - The Id
- Shadowraze damage from 500/1000/1500/2000/2500/3000/3500 to 900/1600/2300/3000/3700/4400/5100 (unchanged for the Id)
- Raze is always centered on Shadow Fiend
- Near radius increased to 450
- Medium radius increased to 700
- Far radius increasd to 950

## Sniper
- Removed Aghanim's Shard and Aghanim's Scepter
- Replaced vanilla facets.
- Shrapnel is no longer the default first ability.
- Take Aim no longer innately increases Headshot's proc chance, instead grants armor as vanilla.

## Sniper: Gunslinger
- Keen Scope: flat 50 attack range bonus, but reduces Sniper's base attack time when Assassinate is leveled.
- Concussive Grenade: Damage increased and scales, other ability values scale. Sniper is knocked back only if he's within the area of effect.
- Headshot: Headshot chance is increased based on how close you are, up to 80% chance. Maximum chance at 250 range, minimum at 800.
- Take Aim: Sniper turns invisible for the duration and attacking does not reveal you. The movement speed slow becomes a movement speed bonus instead.
- Assassinate: Cast point reduced to 0.3 seconds and cast range reduced to 700, hits all units in a 325 radius around the primary target.

## Sniper: Deadeye
- Keen Scope: Attack range unchanged
- Shrapnel: Unchanged
- Headshot: If Headshot triggers against a unit already Headshot, fires an Assassinate projectile that deals 10/15/20/25% of the damage and stun duration. This also triggers if Headshot procs twice on the same attack, such as when Take Aim is active.
- Take Aim: Increases Headshot Chance while active. Headshot chance bonus is 110/115/120/125%
- Assassinate: Assassinate's stun duration is increased from 0.5 to 2s and cooldown from 20/15/10 to 14/11/8.

<div align="center">
  <h1>Bosses</h1>
</div>

## General
- **1.5.3c:** Reduced base armor and base magic resistance values of all bosses, minions now have 0 base armor and 0% base magic resistance
- **1.5.3c:** Minion is now a creature type like Reinforced. Represented by an ability. Whenever a spell deals damage to another unit, all minions gain 50% damage resistance to that spell for 0.5 seconds.
- **1.5.3c:** Champion is now a creature type like Reinforced. Represented by an ability. Bosses take less damage from abilities that deal maximum health damage. The damage resistance formula is 100 x (1-1/Players), for a total of 0/50/66.6/75/80/83.3/85.7/87.5/88.8/90%