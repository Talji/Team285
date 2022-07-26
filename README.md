# Team285
Life is Like - Team 285 Game Camp Development GitHub

Built using [Unreal Engine 5](https://www.unrealengine.com/en-US/download) (Ver 5.0.3)

## 1.1. Game Name: “Life Is Like”

1.2. Tag line: “It’s one thing to know, it’s another to remember.”

1.3. Team: Team 285

1.4. Date of last update: 7/14/22

## 2. Game Overview

2.1. Game Concept: Combination of roguelike and roguelite (skill-based but has progression), provides memorable experience and challenges with high proximity to reality, the player can reflect the game to their lives and vice versa to proceed in the game. The longer you live, the stronger you become.

2.2. Target Audience: 18-35 year old Males that enjoy Narrative Driven Roguelike games

2.3. Genre(s): Fantasy Action/ Adventure Roguelike

2.4. Game Flow Summary: How does the player move through the game? Include both the interface and the game itself. Twin stick style motion, L-Joystick controls movement, R-Joystick controls direction. Movement through levels is linear from start to finish

2.5. Look and Feel: What is the basic look and feel of the game? What is the visual style? Isometric 3D cell shaded, fantasy setting


## 3. Gameplay
3.1. Objectives: What are the objectives of the game?
To gather and put pieces of memory (narrative) together to reveal the story/world 


3.2. Game Progression:
Dead: gain abilities randomly from the ones related to the death, loss all experience point, weapons, gears and money

Remains after death: the stacks of the ability (if it’s the same), conversation/encounter history with NPCs

Alive: spend experience points on unlocking skill tree and money on merchant, both can strengthen the player


Extrinsic: proceed to new areas, new narratives, and staying alive will make you stronger
Intrinsic: knowing the mechanics more and more will reduce the difficulty, and sense of achievement when the huge odds being overcome in the end

3.3. Play Flow: How does the game flow for the game player
Rewards from combat/puzzle-solving and feedback loops to hook the player; synergy among the ability, character weapons and environments; get more familiar with mechanics and rules to reduce difficulty

[In a level]
Early: encounter with new environment, explore to understand the tone, find resources/collectables and have time to plan (applicable synergy and strategy), combat with sporadic enemies, and puzzle-solving

Middle: increase the experience density, start encountering waves of combined types of enemy, the player needs to learn the mechanics, traps and synergies to plan and combat. After several waves, Elite Enemies. Then, provides safe area for purchase/unlock skill tree, rest and plan.

Late: back to exploration and puzzle-solving, more difficult but with richer supply feed, implies the tough battle ahead. Boss Fight.

[Throughout the game]
The experience in levels can be switched and rearranged, and the variations of levels can be arranged for the game to create different paces with difficulties

3.4. Mission/challenge Structure:
Keep providing different challenges to require a variety of strategies and skills
Different environments and corresponding types of enemy, different puzzles


3.5. Puzzle Structure:
Platforms (timing, special move/ability), hint/lore-required, item-required, observation & reasoning, use of mechanics -> can go to some areas but some can’t which increased the replayability


## 4. Mechanics (Key Section)
4.1. Rules – What are the rules to the game, both implicit and explicit
[Implicit]
Player has to learn and adapt to the game - the randomly gained ability (force them to think about the usages and synergies but the latest one has higher possibility to acquire)
All abilities are useful, either for combat or exploration, the player need to explore the potentials on their own

[Explicit]
To find their own way to play the game (can purchase gears and make their own weapons that fits personal usage)
Don’t be reckless (keep surviving = scaling, yet can still die easily)
Learn and plan (the ability gets stronger as one uses, which can also prevent squeezing the ability experiences to dry too soon) [e.g. dash -> double dash (if the 2nd one wasn’t used in a period, ability goes into cooldown) -> dash without collision against enemies]
Think and adapt (1 use of ability = 1 stack, and a max stacked ability can open up another ability slot, as well as synergies of the combination; however, the second slot will be gone after death]


4.2. Model of the game universe. Think of it as a simulation of a world, how do all the pieces interact?
The environments are reactive, and the interactions are intuitive for the player to apply real-life experiences in the game


4.3. Physics – How does the physical universe work?
Some obey real physics, some follow the rules of the fantasy world


4.4. Economy – What is the economy of the game? How does it work?
Killing enemies earn experience points (exp) -> unlock skill tree (more abilities can be acquired after death, persistent) and plot advancement

Selling collectables/explore the environment to earn money ($) -> merchant system (purchase/customize/upgrade weapons and gears, items for combat/exploration)


4.5. Character movement in the game
Basic: up/down/left/right/diagonal/roll
Ability: teleport, dash, double/triple jump, charged sprint


4.6. Objects – how to pick them up and move them
Collide with objects to pick/move them


4.7. Actions, including whatever switches and buttons are used, interacting with objects, and
what means of communication are used
‘E’ 
Conversation between the player and NPCs might have persistent consequences


4.8. Combat – If there is combat or even conflict, how is this specifically modeled?
All enemies will try to attack the player, they are agile, aggressive and fatal. Quick response is required but same as plan in advance and strategies. Enemies will use different means of attack, so as the player. Choose wisely to counter, and use the synergies among weapons, abilities and the reactive environment as a help.

Observe and learn enemies’ attributes and attack patterns -> timing -> dodge/attack
Encouraging the player to attack: attacking enemies can gain Health (HP) and reduce ability CDR, otherwise can only recover from consumables that require a huge amount of rare consumables + $


4.9. Screen Flow -- How each screen is related to every other and a description of the purpose
of each screen
Splash -> Menu -> Gameplay -> Death -> Results -> Loop To Gameplay


4.10. Game Options - What are the options and how do they affect game play?
Optional areas, NPCs encounter -> affect the amount of reward
These optional areas provide deeper understanding of the world/lore. 

4.11. Replaying and saving
Roguelike but has persistence progress like ability and encounter history
Saving happens at the end of each “level” after a boss is defeated. Player is in a loop otherwise - gaining new knowledge. 
4.12. Cheats and Easter Eggs
Tribute to games/developers

## 5. Story and Narrative
5.1. Back story
5.2. Plot elements
5.3. Game story progression
5.4. Cut scenes -- descriptions include the actors, the setting, and the storyboard or script.

## 6. Game World
6.1. General look and feel of world Fantasy
6.2. Areas
6.2.1. General description and physical characteristics
6.2.2. How relate to the rest of the world
6.2.2.1. What levels use it
6.2.2.2. Connections to other areas

## 7. Characters.
7.1. For each character
7.1.1. Back story
Protagonist:
Antagonist:
Supporting Character (Master):

7.1.2. Personality
7.1.3. Appearance
7.1.4. Abilities
7.1.5. Relevance to the story
7.1.6. Relationship to other characters
7.2. Artificial Intelligence Use in Opponent and Enemy
7.3. Non-combat and Friendly Characters

## 8. Levels
Different universes have different mechanic & denv -> enemies/reactive env
It is a systematic game, which means the enemies and env (entities) have perceptions (inputs) of the player and each other, and they can react (outputs) to each other, so that the systems can merge and interact -> immersion & experience uniqueness ↑
Game systems are aware of each other and able to interact under rules; different entities have their own scripted actions/reactions, and those are rules that the player can use for their own benefits. Entities get counters and able to counter
Player can make interesting plans, indirect interaction is allowed and percevable (traps, create ideal env to fight/usage of the ability) -> can complete the levels in various ways -> replayability & fun
Environment damagable/their own mechanics: gravity, physics, means of attacks, weaknesses, strengths 
Entities do not just listen to specific object but input types; they should have their own purpose and corresponding behaviors 
Therefore: level design should be giving the player a goal and not telling them how to achieve it, provides hints and let them discover their own way to achieve it (open areas, lots of entities can help -> make plans)
Levels are designed to force player to keep adapting and have a sense of crisis that they can die easily if they did not play strategically and understand the mechanics in different levels
Connect to provide verisimilitude (increase in belivability)
For example: enemies will pray for power/sacrifice in shrines that is full of interactable statues & traps (the gods they believed in were ancient alien civilizations
8.1. Training Level
8.2. For each level
8.2.1. Synopsis
8.2.2. Required introductory material and how it is provided
8.2.3. Objectives
Clear enemies, control the area, unlock lore


8.2.4. Details of what happens in the level
8.2.4.1. Map
8.2.4.2. Critical path that the player needs to take
8.2.4.3. Important and incidental encounters

## 9. Interface
9.1. Visual System
9.1.1. HUD
9.1.2. Menus
9.1.3. Camera model Isometric 
9.2. Control System – How does the game player control the game? What are the specific
Commands?
B - skill 
A - dash
RB/LB - abilities
X - light attack
Y - heavy attack
9.3. Audio, music, sound effects Lo-Fi Hip Hop Fantasy Vibes
9.4. Game Art – intended style Stylized Cell Shaded 3D
9.5. Help System


## 10. TODO
10.1  Add a .gitignore to prevent adding files we don't want in this repo
10.2 Specify control scheme once implemented  fully
