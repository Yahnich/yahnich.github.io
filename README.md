> EBF 1.6.0b - 11/02/2025
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Maps
- Removed Normal, Hard, Challenger and Nightmare map.
- Replaced these maps with Mayhem and Strategy
- Baseline spawntable is based on Nightmare with Challenger wave delays.
- Increasing the difficulty increases the health by 40%, attack speed by 25%  and attack damage by 10% per difficulty increase for both maps
- Increasing the difficulty increases the respawn timer by 40 seconds. Baseline is 60 seconds.
- Increasing the difficulty increases the MMR gained by +5. Baseline is 15.
- Enrage timer increased from 30 to 90. Increasing the difficulty reduces this by 20s, down to 30 in Nightmare.
- Strategy time between rounds is 60 seconds by default. Each time someone votes to skip, this delay is reduced (total reduction is equal to TimeLeft x 60/Skips). Delay automatically drops to 0 once everyone has voted.
- Players can now vote for difficulty during Strategy time. The difficulty is the one with the most votes, in case of a tie, difficulty is a compromise, rounded down.
- Both maps have all 1 of each camp type.
- Once you load into the game, the game will generate one of three maps: Peaks of Scree'auk, Fields of Endless Carnage and Narrow Mazes. Players are warned what map was chosen at hero select.
- Peaks of Scree'auk is a map with a lot of different elevation where more mobile heroes can lose their opponents.
- Fields of Endless Carnage is a map with a lot of open space that leads to brawls.
- Narrow Mazes is a map where heroes with high movement speed can outmaneuver the opponent.
- Fog of War has been enabled on all maps and difficulties.
- Shop is now global.

## Mayhem
- Has 10 players with no downtime on spawns and doubled spawns.
- Neutrals give no gold and rounds will automatically end after 180 seconds
- Players cannot skip prep time if at least one enemy is alive. Prep time is 30 seconds if an enemy is alive and 0 otherwise.
- Enemy units do not die when a round ends. The next round spawns in addition to the others.
- Increasing the difficulty reduces prep time and round deadline by 16.6% per difficulty increase.

## Strategy
- Has 5 players, with a more traditional 'wave' mechanic with downtime between waves.
- Enemies have baseline 25% increased HP, 10% increased attack damage and 25% increased spell damage.
- Increasing the difficulty reduces the spawn delay between waves by 16.6% per difficulty increase.

## Illusions
- **1.6.0b.** Buffed across the board

<div align="center">
  <h1>Items</h1>
</div>

## Wards
- Observer and Sentry wards are purchasble, no longer have stock or restock time. Cost 100 gold and last 1.5 minutes
- **1.6.0a.** Observer ward vision range is 2400/2400.
- **1.6.0a.** Difficulty increases reduce ward vision by -200/-400

## Smoke of Deceit
- Removed from the game.

## Aghanim's
- **1.6.0b.** All heroes start with their scepter and shard upgrade.

## Monkey King Bar
- **1.6.0b.** Bonus pure damage from attack damage from 0/0/5/10/15% to 0/5/10/15/20%

## Martyr's Bulwark
- **1.6.0b.** Lightning bounces from 4 to 4/5/6/7/8

## Scythe of Vyse
- **1.6.0b.** Cooldown from 36 to 18.
- **1.6.0b.** Units hexed doubled, but chain duration halved (better against horde waves, same against solo waves)

## Radiance
- T1 Radiance burn damage from 300 to 200.

<div align="center">
  <h1>Heroes</h1>
</div>

## Nyx Assassin - Aulacimorph
- Parasitize makes the enemy hostile to both heroes and bosses, damage taken by unit reduced by 75%

## Bloodseeker
- **1.6.0b.** Sanguivore max health regeneration on spell damage from 0.3/0.4/0.6/0.8 to 0.1/0.2/0.3/0.4%
- **1.6.0b.** Sanguivore kill bonus from 400% to 300%
- S**1.6.0b.** anguivore now grants 30% lifesteal from Pure damage.
- **1.6.0b.** Bloodrage's health loss ignores barrier.

## Bloodseeker - Cuauhtli
- **1.6.0b.** Sanguivore: Creep penalty from 20% to 50%.
- **1.6.0b.** Bloodrage: Bloodseeker deals 200/250/300/350 bonus Pure damage every attack. Additionally, when one or less Hero units are in range of Bloodseeker, all of Bloodrage's benefits are increased by 50%.
- **1.6.0b.** Blood Rite: Bloodseeker passively deals 25% more damage from all sources against Silenced units.
- **1.6.0b.** Thirst: When Bloodseeker has an attack target or attacked a unit within the last 1.5 seconds, Thirst's scaling is inverted, granting him more movement speed the higher his health is. Additionally, at 80% strength, Bloodseeker gains flying movement.
- **1.6.0b.** Rupture: Rupture deals double damage against units being attacked by Bloodseeker.

## Bloodseeker - Ocelotl
- **1.6.0b.** Sanguivore: Bloodseeker gains a 400 radius aura that deals damage equal to 25% of his missing health to all enemies.
- **1.6.0b.** Bloodrage: While Bloodrage is active, all health gained by Bloodseeker is turned into barrier, up to 100/133/166/200% of his missing health total.
- **1.6.0b.** Blood Rite: No longer point-targeted. Instead, the ritual follows Bloodseeker and has its radius doubled.
- **1.6.0b.** Thirst: Bloodseeker gains up to 5/10/15/20 bonus armor based on his missing health.
- **1.6.0b.** Rupture: The initial burst damage is dealt to all units within 400 units of the target. All units affected by the burst damage are affected by Rupture.

## Pudge
- **1.6.0b.** Removed Aghanim's Scepter and Shard upgrades.
- **1.6.0b.** Removed vanilla facets.
-**1.6.0b.**  Meat Hook's remaining cooldown is halved if you did not hit an enemy unit with it.

## Pudge - Rotten Giant
- **1.6.0b.** Flesh Heap: Flesh Heap grants Pudge an additional 5/6/7/8 maximum health per stack.
- **1.6.0b.** Meat Hook: Pudge gains 3/5/7/9 armor and 5/10/15/20% magic resistance when he casts Meat Hook, which lingers for 4 seconds. 
- **1.6.0b.** Rot: Rot damage increases by 30/60/90/120 every second. Pudge takes 60% of Rot's damage.
- **1.6.0b.** Meat Shield: When activated, heals Pudge for 800/1400/2000/2600 and applies a Basic Dispel.
- **1.6.0b.** Dismember: Cast range is increased to 400 and is now a 250 radius point-targeted ability. Pudge gains 20/40/60 Strength every second for each affected Hero.

## Pudge - Flesh Carver
- **1.6.0b.** Flesh Heap: Flesh Heap grants Pudge an additional 1/2/3/4 base damage per stack.
- **1.6.0b.** Meat Hook: Enemies hooked take 100% of the distance travelled as Pure damage. Additionally, Hook reduces enemy armor by 1/2/3/4 and magic resistance by 3/6/9/12% for 4 seconds. The duration increases in duration instead of ticking down while travelling.
- **1.6.0b.** Rot: While Rot is active, Pudge gains 4/8/12/16% bonus attack damage every second, up to 20/40/60/80% max bonus attack damage after 5s. Once Rot is deactivated, damage bonus rapidly decays over 1s.
- **1.6.0b.** Meat Shield: While active, Pudge gains 10/15/20/25% bonus phased movement speed.
- **1.6.0b.** Dismember: While Dismembering, Pudge gains 5/10/15% outgoing damage amplification every tick for 8 seconds. Duration is refreshed each time and stacks up to 15/30/45%.

## Riki
- **1.6.0b.** Removed Aghanim's Scepter and Shard upgrades.
- **1.6.0b.** Removed vanilla facets.
- **1.6.0b.** Smoke Screen no longer guarantees Backstab.
- **1.6.0b.** Applying Blink Strike now increases any remaining duration, instead of just refreshing it.
- **1.6.0b.** Tricks of the Trade cast range increased from 400 to 700

## Riki - Infiltrator
- **1.6.0b.** Cloak and Dagger: Instantly kills non-hero units.
- **1.6.0b.** Smoke Screen: Riki always benefits from Cloak and Dagger while inside of Smoke Screen.
- **1.6.0b.** Blink Strike: Cloak and Dagger activates immediately after Blink Strike.
- **1.6.0b.** Backstab: Deals half damage when not attacking a creature from the back.
- **1.6.0b.** Tricks of the Trade: Killing non-hero units reduces the cooldown of Tricks of the Trade by 0.75 seconds.

## Riki - Revolutionary
- **1.6.0b.** Cloak and Dagger: Cloak and Dagger Disarms enemies for 1.2 seconds. Duration is frozen against Stunned enemies.
- **1.6.0b.** Smoke Screen: Radius increased from 425 to 600 and enemies lose 2/3/4/5 armor while within Smoke Screen.
- **1.6.0b.** Blink Strike: Stun/Slow duration increased to 1.2 seconds.
- **1.6.0b.** Backstab: Backstab heals all allies within 450 units of the attack target for 25% of Backstab's bonus damage.
- **1.6.0b.** Tricks of the Trade: Can be unit-targeted. If an allied hero is targeted, they gain the bonus Agility and Tricks of the Trade is centered on your ally.

<div align="center">
  <h1>Bosses</h1>
</div>

## Gnolls
- Troll Warlord Boss has decided to reinforce this wave.

## Ogres
- Troll Warlord removed from this round.

## Minions
- All minion units health reduced between 40-60%.
- Minion-type ability now reduces the damage taken from AoE abilities from 50% to 75%
- Minions no longer scale in health and damage with player count at all, instead more minions are spawned.
- If a new minion would be spawned and there is a maximum number of units, instead, the oldest unit is upgraded, increasing their health and damage.
- Minion health now has a 20% variance, having anywhere from 80-120% base health.

## Butchers
- **1.6.0b.** Reduced hook base damage from 1000 to 500.
- **1.6.0b.** Reduced hook travel damage from 100% to 50%