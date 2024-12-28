Burning Hay:            Campaign is created by "Amaroth"
Contact (Discord):      amaroth
Distributed under:      CC BY license
Initial release:        14-04-2024


**---CHANGELOG---**
**#V2.2**
**Mission 7**
- Added a new mission, Gold Rush. This mission is a follow-up to the Mining Trouble, continuing the fight on the same map, just expanded to the West. A new mercenary mechanic is introduced in this map, and the player has for the first time everything (except knights) unlocked and available. The mission's challenge lies in a very aggressive T3-heavy enemy and in the player's base being very open to the attacks.

**Mission 8**
- Added yet another mission, Red Dawn. This is the second battle-only mission, which brings in a very large-scale battle against numerous enemy units. The enemy units also employ advanced tactics, making sure the player is kept on their toes. The score system is the same like for mission 4, except the time limit is increased to 30 minutes. All of the troops also get indefinitely fed in this mission.

**Mission 3**
- Added camera snap-ons when burned villages are discovered.

**Mission 5**
- Fixed an issue where Royce could be present more than once on the map.
- Gave Royce a damage buff.
- Upon his arrival, the camera focuses on Royce. Same goes for Aston.
- Added camera snap-ons when bridges and other points of interest are discovered.
- If the siege camp is fully defeated, Royce's troops no longer waste time burning the rest of it to the ground and start attacking Hargrave instead.
- Added an additional quest for discovering the siege camp's supply road.
- Royce's lone peasant is now corrently removed on mission's startup.
- Weakened Hargrave's defense on the castle's side.

**Mission 6**
- Captain Aston is now present on the map.
- Trader's markers were improved and made more clear.
- Albrecht's daughter added into the dialogues.
- Camera focus on traders when they are met, and when a player's unit is spotted.

**Other improvements**
- Updated the campaign's description to manage the expectations better.
- All missions: overall story editing for grammar, style, flow and pacing.



**#V2.1**
**Mission 4**
- Score is now: kills / losses (min 1) * ((12000 - time in ticks): min 600) OR 0 if the player is defeated. Basically, half your losses OR half your time in comparison with the 20 minute deadline to double your score.
- Increased AI support/aggression radius. Frontal assaults will now pull the enemy army the way they should.
- "Hargrave escaped" message now properly pops out when all enemy knights are dead.
- Hargrave now properly doesn't count as a defeated enemy in the mission score and the amount of enemies killed.
- More code cleanup, objective info displays adjustments.



**#V2**
**Mission 6**
- New Chapter 2 was added, together with its intro mission number 6, Mining Trouble. The following missions are still under development.

**Heroes**
- Each mission now starts with one or more heroes on the map. These are regular units, however, they have changed name, HP and color. Their HP regeneration is also changed, so they fully heal within 3 minutes (+20 seconds after they escaped their last fight). Stats of the main heroes also progressively increase throughout the missions. Currently, there are 7 different heroes present in the campaign: Haytow, Aston, Graham, Linton, Hargrave, Royce, Albrecht.

**Day-night cycle**
- The day-night script I posted earlier was completely overhauled. Now it's fully customizable and easy to integrate into already existing map's script. The new cycle was added into all maps.

**Better AI**
- The entire AI scripting for attacks was completely overhauled. Archers now shoot when sent to attacks, performance issues were fixed, units "helicoptering" were fixed, errors caused by troops in towers were removed. The AAI script is now also stand-alone and can be easily integrated into any already existing map's script.
- AI can now determine when to feed sheep and/or horses, and when not. It can also block wares from its storehouse when they are in abundance, reducing unnecessary porter traffic.
- AI can now check which troop types have no free formations to train new troops into. It will then redirect its efforts to producing armaments and training troops it actually misses and needs.
- AI now has several small formations of troops guarding its town and key buildings in missions, where this change was needed. This should help with AI being helpless when its town is invaded after circumventing its main army.

**New map**
- Completely new campaign map was made using Inkarnate Pro.
- New/revised campaign map icons.

**Other improvements**
- Blocked units and houses were updated throughout the missions.
- Missions now start with some areas uncovered from Haytow's scouts.
- Mission objectives and their completion tracking systems were completely overhauled. In some missions, the objectives were made more clear/intuitive.
- libx translation keys were fully changed into human-readable format.
- Overall mission-specific script code overhauls and large scale cleanups.

**Mission-specific changes**
- Mission 1: Bandits now target units as well.
- Mission 2: All bandit units have to be defeated now as well.
- Mission 3: Villagers now train rebels with forks instead of militia. Marauders get more horses at the start of the mission, and have more porters. Marauders have revised and more numerous army positions.
- Mission 4: Some score calculation fixes, and enemy scouts are now visible at the beginning of the mission. Hargrave is now briefly visible in the mission as well.
- Mission 5: Hargrave receives extra Stables. His attacks were overhauled and are overall deadlier. Siege camp now takes part in the attacks as well.
- Mission 6: Since the early playtest, an objective was added for talking with the traders, reinforcements arrive times were added to the objective trackers, and some other minor fixes and tweaks were made.



**#V1:**
- Initial campaign's release. Chapter 1 (missions 1 - 5).