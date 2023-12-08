> EBF 1.32.11 - 17/11/2023
<style>
  body {
  background-color: #151618;
  color: rgba(187,187,187,.9333333333);
  }
</style>


<div align="center">
  <h1>General</h1>
</div>

## Round Scaling
- Boss Damage and Health no longer scales linearly with player count, more/less units are spawned at certain breakpoints. Health and Damage still scales up if a breakpoint isn't reached.
- Tuned up baseline Health scaling from +75% diminishing to +100% diminishing.

## Enrage
- Enrage now gives units unobstructed movement after 5 stacks.

<div align="center">
  <h1>Items</h1>
</div>

## Voodoo Mask
- Spell Lifesteal from 8% to 3%

## Blood Gem
- Lifesteal from 10.5/11/11.5/12% to 7%

## Bloodstone
- Spell Lifesteal from 11/14/17/20/23% to 5/7/9/11/13%
- Spell Lifesteal Active Multiplier from 2/2.3/2.6/2.9/3.2 to 2/2.5/3.5/4.5/6

## Kaya and Sange
- Spell Lifesteal from 9/11/13/15% to 4%/5%/6%/8%

## Morbid Mask
- Lifesteal from 9% to 6%

## Mask of Madness
- Lifesteal from 10% to 6.5%

## Satanic
- Lifesteal from 14/15/17/19/21% to 8.5/11/13.5/16/18.5%

## Uber Dagon
- Spell Lifesteal from 8/9/10/11/12% to 3/3.5/4/4.5/5/6%

## Vladmir's Offering
- Lifesteal from 9% to 6/7/8/9/10%

## Yasha and Kaya
- Lifesteal from 10/11/22% to 6.5%/8%/10%


<div align="center">
  <h1>Heroes</h1>
</div> 

## Abaddon
- Aphotic Shield Barrier from 800/1600/3200/6400/15000/30000/60000 to 800/1200/2000/3000/4500/8000/15000 (still scales with Spell Amplification)
- Aphotic Shield Barrier to Damage from 100% to 400%
- +50% Aphotic Shield Barrier to Damage to +200%

## Omniknight
- Purification Heal from 1500/2870/6440/12960/24790/59695/112000 to 1500/2500/4500/8500/18000/27500/50000
- Purification Damage from 2420/3690/5080/7730/14100/25860/53350 to 1200/2100/3500/6500/11000/18000/30000
- Repel cooldown from 26/22/18/14/11.85/9.7/7.55 to 14
- Repel Base Strength from 40/110/250/500/750/1000/1500 to 50/100/150/250/400/600/800
- Repel Bonus Strength per Debuff from 25/45/75/150/350/650/1350 to 20/40/60/100/160/250/350
- Repel Health Regen from 80/180/405/915/2100/4650/10500 to 100/200/350/650/1250/2000/3500
- Repel Duration from 10 to 5/6/7/8/9/10/11
- +200% Purification damage/healing talent to +100%
- +1150 Strength Per Debuff talent to +75%

## Io
- Tether Heal Amplification from 60/80/100/120/140/160/180% to 60%
- Shard Overcharge Spell Lifesteal from 10% to 4%
- Shard Overcharge Spell Amplification from 10% to 25/40/55/70/85/100/115%
- Sacrifice cooldown from 90/75/60/53.3/46.7/40.0 to 120/110/100/90/80/70

## Witch Doctor
- Voodoo Restoration healing from 175/375/655/1010/2085/4250/8600 to 35/85/150/275/500/950/1750
- Voodoo Restoration healing to enemy damage from 50% to 300% (from 87/187/327/505/1042/2125/4300 to 105/255/450/825/1500/2850/5250)
- Voodoo Restoration mana cost per second from 10/20/40/80/120/160/240 to 15/20/30/45/65/90/120

<div align="center">
  <h1>Bosses</h1>
</div>

## Round 1 - Kobolds
- Kobold Serf base attack damage from 95-125 to 65-75
- Kobold Warrior base attack damage from 80-110 to 55-70
- Kobold Overseer base attack damage from 125-150 to 85-100

## Round 2 - Gnolls
- Gnoll Assassin base attack damage 75-100 to 50-70
- Gnoll Berserker base attack damage 175-225 to 115-140
- Gnoll Berserker Death Throe: Damage from 90/120/150% to 100/150/200%

## Round 3 - Zombies
- Raging Zombie base attack damage from 175-225 to 115-140
- Zombie Spitter base attack damage from 155-205 to 100-135
- Zombie Lord base attack damage from 350-450 to 230-295
- Zombie Lord Soul Rip damage per unit from 45/55/65 to 30/40/50
- Zombie Lord Decay damage from 400/450/500 to 320/360/400
- Zombie Lord Tombstone health scaling now has diminishing returns after 5 and 8 players (3 for first 5 heroes, 2 per hero from 6 to 8 and +1 afterwards (from 15/24/30 for 5/8/10 players to 15/21/23 for 5/8/10 players)
- Zombie Torso base attack damage from 350-450 to 200-250

## Round 4 - Darkreef Thugs
- Darkreef Bruiser base attack damage from 400-500 to 260-325
- Darkreef Rogue Pounce damage from 200/300/400 to 160/240/320
- Darkreef Rogue base attack damage from 1000-1200 to 650-800
- Darkreef Rogue Bloodrite damage from 1750 to 1400

## Round 5 - Lifestealers
- Lifestealer base attack damage from 650-800 to 425-515

## Round 6 - Robots
- Clockwerk Mecha base attack damage from 2000-4000 to 1560-2340
- Clockwerk Mecha Battery Assault damage from 225/300/375 to 180/240/300
- Clockwerk Mecha Power Cogs damage from 1750/2250/2750 to 1150/1450/1750

## Round 7 - Slithereen
- Slithereen Queen base attack damage from 1400-1600 to 910-1040
- Slithereen Queen Bash of the Deep damage from 1250/1500/1600 to 800/975/1150
- Slithereen base attack damage from 1500-3000 to 1200-1800
- Naga Illusionist base attack damage from 1500-2500 to 1000-1600
- Naga Illusionist Riptide damage from 550/600/750 to 440/480/520
- Tidehunter Ravager base attack damage from 5000-6500 to 3250-4225

## Round 8 - Roshan Beasts
- Roshan Beast base attack damage from 2500-3200 to 2000-2560

## Round 9 - Leshrac Destroyers
- Leshrac Destroyer base attack damage from 1000-2000 to 800-1200
- Leshrac Destroyer Pulse Nova damage from 500/600/700 to 350/420/490
- Leshrac Destroyer Split Earth damage from 16000/18000/20000 to 12800/14400/16000
- Leshrac Destroyer Split Earth stun time from 2 to 1
- Leshrac Destroyer Split Earth secondary split time from 3 to 2

## Round 10 - Golems
- Granite Golem base attack damage from 12000-15000 to 8000-9500
- Granite Golem Rock Throw damage from 6000/10000/18000 to 4000/6500/12000
- Mud Golem base attack damage from 4000-6000 to 2750-4000

## Round 11 - Ogres
- Ogre Defender base attack damage from 7500-9000 to 4875-5850
- Ogre Magi base attack damage from 6100-8200 to 4000-5300
- Ogre Magi Ignite damage per sec from 1000/1250/1500 to 800/1000/1200
- Ogre Magi Frost Shield pulse damage from 1000/1250/1500 to 800/1000/1200
- Ogre Destroyer base attack damage from 10000-12000 to 6500-7800
- Ogre Minion base attack damage from 5000-5500 to 3250-3750
- Troll Warlord base attack damage from 5250-6500 to 3500-4500
- Troll Warlord Throw Axes damage from 5000 to 3500

## Round 12 - Treants
- Forest Guardian base attack damage from 20000-35000 to 14400-21600
- Forest Guardian Overgrowth damage per sec from 1500/1750/2000 to 1200/1400/1600
- Forest Summoner base attack damage from 12000-18000 to 9600-14400
- Forest Summoner Wrath of Nature damage from 2250 to 1800
- Treant base attack damage from 9000-12000 to 5850-7800
- Greater Summoner base attack damage from 12000-15000 to 7800-9750

## Round 13 - Axes
- Crimson Reaver base attack damage from 15000-20000 to 9750-13000
- Crimson Gremlin base attack damage from 7500-10000 to 5000-6500

## Round 14 - Dragons
- Ancient Dragon base attack damage from 15000-20000 to 10000-14000
- Ancient Drake base attack damage from 12000-18000 to 8000-12000

## Round 15 - Prophets
- Divine Prophet base attack damage from 18000-25000 to 12000-17000

## Round 16 - Skeleton King
- Skeleton Archer base attack damage from 12000-15000 to 8000-10000
- Skeleton Vanguard base attack damage from 20000-30000 to 13000-19500
- Skeleton Minion base attack damage from 10000-20000 to 8000-12000
- Skeleton King base attack damage from 40000-60000 to 26000-39000

## Round 17 - Bears
- Mini Ursa base attack damage from 12000-14000 to 7800-9100
- Ursa base attack damage from 12000-14000 to 7800-9100
- Beastmaster base attack damage from 22000-33000 to 15000-21000
- Spirit of the Forest base attack damage from 35000-50000 to 22750-32500
- Bear Fury Swipes damage per stack from 1000/1250/1500 to 650/825/1000

## Round 18 - Nyx Assassin
- Nyx base attack damage from 30000-35000 to 20000-22750

## Round 19 - Warlock Golems
- Warlock Golem Fire Strike damage from 125000/12500/150000 to 80000/90000/100000

## Round 20 - Warlock
- Warlock True Form base attack damage from 45000-50000 to 30000-32500

## Round 21 - Twin Demons
- Shadow Demon base attack damage from 100000-120000 to 65000-78000
- Shadow Fiend base attack damage from 100000-120000 to 65000-78000
- Eidolon base attack damage from 50000 to 32500

## Round 22 - Necrophos
- Necrophos base attack damage from 100000-140000 to 62500-95000

## Round 23 - Doom
- Doom base attack damage from 133333-166666 to 86666-109999

## Round 24 - Asura
- Asura base attack damage from 166666 to 86666
