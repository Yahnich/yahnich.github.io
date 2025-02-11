> EBF 1.6.0 - 11/02/2025
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
- Increasing the difficulty increases the health and spell cooldowns by 25% and attack damage by 10% per difficulty increase for both maps
- Increasing the difficulty increases the respawn timer by 40 seconds. Baseline is 60 seconds.
- Increasing the difficulty increases the MMR gained by +5. Baseline is 15.
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

<div align="center">
  <h1>Items</h1>
</div>

## Wards
- Observer and Sentry wards are purchasble, no longer have stock or restock time. Cost 100 gold and last 1.5 minutes

## Smoke of Deceit
- Removed from the game.

<div align="center">
  <h1>Heroes</h1>
</div>

## Nyx Assassin - Aulacimorph
- Parasitize makes the enemy hostile to both heroes and bosses, damage taken by unit reduced by 75%

<div align="center">
  <h1>Bosses</h1>
</div>

## Minions
- All minion units health reduced between 40-60%.
- Minion-type ability now reduces the damage taken from AoE abilities from 50% to 75%
- Minions no longer scale in health and damage with player count at all, instead more minions are spawned.
- If a new minion would be spawned and there is a maximum number of units, instead, the oldest unit is upgraded, increasing their health and damage.
- Minion health now has a 20% variance, having anywhere from 80-120% base health.
