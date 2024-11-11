> EBF 1.5.3b - 14/10/2024
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
- Treasure round removed, players now start with 6000 gold and start at level 1.
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
- **1.5.3.a:** Item drops are no longer limited by round, you can obtain a Tier 5 (Bahamut) item round 1.
- **1.5.3.a:** This is weighted, the higher the round number, the higher the chances are of you obtaining a high-level item
- **1.5.3.a:** Item chances are 80/10/5/3.5/1.5% for Tier 1/2/3/4/5 items at round 1. Every round reduces the Tier 1 item chance by 8%, granting 4.0/2/1.25/0.75% to the other tiers.
- **1.5.3.a:** Tier 1 chance is 0% after round 10, after which the item chances are 0/50/25/16/9%. Each round after this reduces the Tier 2 chance by 5% and increases the chances of the other items by 2.5/1.5/1%; reaching a maximum after round 20 of 0/0/50/31/19%.
- **1.5.3.a:** Added 1 additional Tier 4 round (pool consists of asura, doom, necrophos, etc), meaning there are now 25 instead of 24 rounds
- **1.5.3.a:** Selling dropped items no longer grants gold. You can still sell items you bought yourself and dropped items you've upgraded as normal.
- **1.5.3.a:** Heroes start with Aghanim's Shard and Scepter upgrades

## Ability Scaling
- Hero initial base damage now scales with hero power, mostly affects earlygame attack damage output.
- Ability power renamed to Hero Power now that it affects more things
- Ability power scaling from +30% per level to +20%.
- +35% Base Attributes talent changed to +1% Hero Power/Level
- You no longer get free skill points level 17, 18 and 19
- Reworked ability levels. All abilities now have the standard vanilla amount of levels. Basic abilities have 4 levels, ultimate abilities have 3.
- Cooldowns and durations are reverted to vanilla scaling
- Removed spell amplification scaling from primary attributes. You still gain provides 0.2% spell amplification per 10 Intelligence.
- Primary attribute now directly increases the base damage of your spells, similar to ability power. Only affects spell damage, all other values are unaffected. Spell damage increase is 0.2% per 10 Primary. Multiplicative with ability power.
- Ex (Lv13 Lina, 520 Intelligence). Level 7 Dragon Slave: 18840 damage (360% ability power x 20.8% spell amplification) / Level 4 Dragon Slave: 7661 damage (240% ability power x 7.5% spell amplification x 7.5% base spell damage)
- Ex (Lv30 Lina, 6245 Intelligence). Level 7 Dragon Slave: 115025 damage (870% ability power x 249.8% spell amplification) / Level 4 Dragon Slave: 146361 damage (870% ability power x 124.9% spell amplification x 124.9%)
- Overall damage values are weaker earlygame (the example does not include stats from items), but can peak higher lategame. Spell amplification items have more impact.

<div align="center">
  <h1>Items</h1>
</div>

<div align="center">
  <h1>Heroes</h1>
</div>

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

<div align="center">
  <h1>Bosses</h1>
</div>