# 🎮 CS464 Assignment 01: Game Analysis & Level Blockouts

**Student:** Mustafa Fawwaz | **Roll Number:** BSSE23036

This repository contains my breakdown of two mobile games using the MDA (Mechanics, Dynamics, Aesthetics) framework, along with the Bartle player taxonomy, followed by five custom level blockout designs.

---

## Game 1: Shadow Fight 2

- **Genre:** Fighting / RPG
- **Playtime:** 35 minutes
- **Store Link:** https://play.google.com/store/apps/details?id=com.nekki.shadowfight

<p>
<img src="Docs/shadow_fight/3.jpg" width="240">
<img src="Docs/shadow_fight/2.jpg" width="240">
<img src="Docs/shadow_fight/4.jpg" width="240">
<img src="Docs/shadow_fight/5.jpg" width="240">
</p>

**Visual References:**

- **(M1, M2):** The top energy meter and the gear upgrade screen where players spend coins.
- **(M6):** The in-game Skill Tree.
- **(M3):** A successful Headhit multiplier in action.
- **(M5):** Casting an unblockable Shadow Energy magic attack.

### MDA & Player Taxonomy Breakdown

| Core Mechanic                                                              | Resulting Dynamic                                                                                      | Aesthetic Experience                                                         | Bartle Player Type                                                     |
| :------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| **Energy System:** Fights cost 1 energy, which refills in real-time.       | Players engage in short gameplay bursts, fitting the game easily around their daily schedule.          | **Submission:** Functions as a low-friction, daily routine.                  | **Achiever:** Provides a slow, steady progression ladder to climb.     |
| **Gear Upgrading:** Spending coins to increase base stats.                 | When a boss is mathematically too hard, players grind repeatable modes to hoard coins for better gear. | **Challenge:** Overcoming statistical walls through preparation.             | **Achiever:** Beating the game on its own terms by maximizing stats.   |
| **Positional Hit Multipliers:** Head hits deal bonus damage and shock.     | Players rely on defensive spacing to bait attacks and carefully aim high strikes.                      | **Sensation:** The visceral reward of landing a massive critical hit.        | **Explorer:** Figuring out the nuances of weapon hitboxes and physics. |
| **Survival Mode:** Fighting up to 10 opponents on a single health bar.     | Players drop risky moves and switch to safe, long-range weapons to conserve their health.              | **Challenge:** Testing combat endurance and mastery of safe play.            | **Achiever:** Conquering a tough mode for maximum payouts.             |
| **Shadow Energy:** Filling a meter to cast unblockable spells.             | Players hold onto their magic for clutch moments, using it to interrupt deadly boss combos.            | **Fantasy:** Fulfilling the power fantasy of being a magical shadow warrior. | **Achiever:** Mastering a specific system to gain an edge.             |
| **Skill Tree Perks:** Mutually exclusive passive buffs unlocked per level. | Players test various perk combinations to build an optimal loadout for their preferred weapon.         | **Expression:** Creating a fighting style that fits personal preference.     | **Explorer:** Tinkering with the RPG mechanics to find synergies.      |
| **The Underworld Raids:** Asynchronous group boss fights.                  | Players coordinate with their clan, optimizing high-DPS combos to rank well.                           | **Fellowship:** Teaming up with real people for a shared goal.               | **Killer:** Competing on leaderboards to out-damage peers.             |

### Analytical Conclusion

**Aesthetic Profile:** _Shadow Fight 2_ leans heavily on **Challenge** and **Submission**. The gameplay loop demands mastery over difficult combat physics and stamina management (Challenge), but the energy timers and upgrade economy force the player to engage with it as a background, daily pastime (Submission).

**Target Audience:**

- **Primary (Achievers):** The game is built for players who want to act on the world by climbing strict tournament ladders, grinding levels, and upgrading gear to overpower the AI.
- **Secondary (Explorers):** Players who love interacting with the world to test different weapon ranges, physics quirks, and perk synergies.

---

## Game 2: Zombie Tsunami

- **Genre:** Endless Runner
- **Playtime:** 20 minutes
- **Store Link:** https://play.google.com/store/apps/details?id=net.mobigame.zombietsunami

<p>
<img src="Docs/zombie_tsunami/5.jpg" width="240">
<img src="Docs/zombie_tsunami/4.jpg" width="240">
<img src="Docs/zombie_tsunami/1.jpg" width="240">
<img src="Docs/zombie_tsunami/2.jpg" width="240">
</p>

**Visual References:**

- **(M2):** A large zombie horde clearing a gap and infecting a standing civilian.
- **(M3):** The horde successfully meeting the 4-zombie threshold to flip a bus.
- **(M5):** The horde grabbing a '?' mystery box.
- **(M5):** The resulting transformation after activating the mystery box.

### MDA & Player Taxonomy Breakdown

| Core Mechanic                                                                      | Resulting Dynamic                                                                                                                       | Aesthetic Experience                                                          | Bartle Player Type                                                         |
| :--------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------- | :------------------------------------------------------------------------- |
| **Variable-Duration Jump:** Holding input alters jump width and height.            | Players adjust their jump length based on the size of their horde so trailing zombies don't fall off ledges.                            | **Sensation:** The satisfying rhythmic, wave-like motion of the mob.          | **Achiever:** Beating physical obstacles using precise timing.             |
| **Civilian Infection:** Touching civilians adds them to your zombie horde.         | Players aggressively hunt civilians to build a larger buffer against upcoming hazards.                                                  | **Fantasy:** The make-believe empowerment of leading an unstoppable outbreak. | **Achiever:** Pushing a visible numerical counter as high as possible.     |
| **Vehicle Thresholds:** Flipping cars/buses requires a specific number of zombies. | Players must do split-second math to decide if they can crash into a vehicle for rewards, or if they need to jump it to survive.        | **Challenge:** Rapid risk calculation while moving at high speeds.            | **Achiever:** Clearing high-tier obstacles for the best rewards.           |
| **Zero-Count Loss:** The run only ends when the zombie count reaches zero.         | Players treat extra zombies as an expendable shield, willingly sacrificing them to landmines to keep the run alive.                     | **Challenge:** Managing zombie count to maximize distance.                | **Achiever:** Acting on the system to set personal best records.           |
| **Mystery Box Transformations:** The '?' box grants temporary invulnerability.     | Players abandon cautious platforming and aggressively steamroll through every obstacle on the screen.                                   | **Fantasy:** The extreme power trip of destroying previously lethal hazards.  | **Explorer:** Testing out how different mutations interact with the world. |
| **Potion Vial Missions:** Completing 3 modular tasks to level up.                  | Players change their standard survival strategy to force specific scenarios, sometimes sacrificing a good run just to hit an objective. | **Challenge:** Following a strict checklist of constraints.                   | **Achiever:** Ticking off milestones to climb the level ladder.            |
| **100-Brain Lottery:** Collecting 100 brains earns a scratch-off ticket.           | Players grind "just one more run" specifically to reach the threshold and reveal their lottery prize.                                   | **Submission:** A low-friction gameplay loop driven by simple collection.     | **Achiever:** Incrementally working toward a guaranteed reward.            |

### Analytical Conclusion

**Aesthetic Profile:** _Zombie Tsunami_ thrives on **Fantasy** and **Challenge**. It perfectly captures the chaotic power fantasy of being an unstoppable undead wave, while the actual gameplay loop tests the player's reaction time and instant arithmetic to keep the horde alive at high speeds.

**Target Audience:**

- **Primary (Achievers):** The design caters to players who want to impose themselves on the system to drive up metrics—expanding the horde, flipping the biggest vehicles, and grinding potion ranks.
- **Secondary (Explorers):** Players who enjoy interacting directly with the game's mechanics, discovering how variable jumps work with huge hordes, and testing the limits of the '?' box mutations.

---

## Part 3: Level Blockouts

Below are the five original level blockouts designed for this assignment, each utilizing specific wayfinding tools to guide the player:

| Level        | Preview                                                     | Design Concept                                                                                                                                                  | Wayfinding Tool Used                                                                                                                       |
| :----------- | :---------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| **Level 01** | <img src="Docs/levels/level01.png" width="320" height="50"> | A linear parkour stunt track designed to test momentum. Features include 45-degree ramps, jump gaps, and a narrow cylinder bridge.                              | **Landmark:** A tall goal flag is clearly visible at the end of the straight path.                                                         |
| **Level 02** | <img src="Docs/levels/level02.png" width="320">             | A straightforward vertical ascent utilizing a continuous 45-degree ramp, leading straight into an elevated room to claim a treasure.                            | **Light and Contrast:** A bright point light illuminates the treasure waiting inside the dark upper room.                                  |
| **Level 03** | <img src="Docs/levels/level03.png" width="320">             | An elevated arena accessed via a ramp that splits into two routes: players can choose the safe solid perimeter or attempt to jump across the central platforms. | **Framing:** Two vertical pillars at the top of the ramp naturally frame the entrance to the diverging paths.                              |
| **Level 04** | <img src="Docs/levels/level04.png" width="320">             | A long, dark, enclosed tunnel acting as a structural pinch, which abruptly releases the player out into a brightly illuminated courtyard filled with foliage.   | **Pinch and Release:** The tight, roofed tunnel naturally funnels the player toward the bright, open yard at the end.                      |
| **Level 05** | <img src="Docs/levels/level05.png" width="320" height="60"> | A mid-air vehicle stunt track featuring a long approach ramp, a massive hollow cylindrical tunnel, and a steep drop down to a landing pad.                      | **Framing:** The hollow pipe acts as a tunnel, visually and physically funnelling the player's trajectory straight toward the landing pad. |
