[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Ahsan Uz Zaman Asif]
### Student number: [47499885] 


Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience 
Introduction and Overview

In designing a single-level 2D platformer game, the primary goal was to craft an engaging and rewarding experience that challenges the player's skills in navigation,
combat, and puzzle-solving. The level is divided into three distinct sections, each introducing new mechanics and obstacles, thus keeping the gameplay fresh and compelling.
This design approach not only promotes a deep understanding and mastery of the game's mechanics but also ensures that players remain invested through a carefully balanced
mix of challenges and rewards.

Section 1: Introduction and Mastery of Basic Mechanics
The first section of the level serves as an introduction to the game's core mechanics, including movement, melee combat, and the importance of checkpoints. Upon acquiring
the staff, players learn to engage with enemies at close range, offering a hands-on approach to combat. The presence of an acid pool immediately after teaches players to be
cautious and observant of their surroundings, subtly encouraging exploration for safer routes or solutions.

Example: The placement of the staff before encountering enemies ensures players have the means to defend themselves, thereby reducing frustration and encouraging experimentation
with combat mechanics.
DocImages/2D_Game_1.png
DocImages/2D_Game_2.png
Section 2: Expanding the Arsenal and Introducing Ranged Combat
As players progress to the second section, they acquire a gun, expanding their combat options. This section is designed with enemies placed in such a manner that melee attacks
are less effective, nudging players towards mastering ranged attacks. The inclusion of a key within this section serves as both a goal and a reward, reinforcing the exploration
aspect as players must navigate through enemies and potentially hidden paths to find it.

Example: An enemy positioned on a higher platform unreachable by melee attacks incentivizes players to use the gun, teaching them the value of ranged combat in overcoming obstacles.
DocImages/2D_Game_3.png
DocImages/2D_Game_4.png

Section 3: Culmination of Skills and Ultimate Challenge
The third section is the most densely packed with enemies and traps, designed to test the player's mastery of both melee and ranged combat, as well as their navigation and
timing skills. The layout necessitates careful movement and precision jumping, integrating the skills acquired in previous sections into a cohesive challenge. The final key's
acquisition and the subsequent opening of the door to finish the game serve as the ultimate reward, symbolizing mastery and achievement.

Example: A series of platforms over a perilous drop, with enemies positioned to attack from distance, challenges the player to time their jumps carefully while managing threats,
thus encapsulating the game's core mechanics in a single, engaging encounter.
DocImages/2D_Game_5.png

Conclusion: Ensuring a Cohesive and Rewarding Player Experience
Throughout the level, checkpoints strategically placed at the start of each section not only mitigate frustration by saving progress but also signify the transition between
different gameplay focuses—from mastering individual mechanics to synthesizing these skills in complex scenarios. This deliberate pacing ensures that players feel a continuous
sense of progression and achievement.
DocImages/2D_Game_6.png

The design choices, from weapon placement to enemy and obstacle arrangement, are all aimed at fostering a learning curve that is challenging yet fair. By rewarding exploration with
essential items (like keys) and offering varied combat scenarios, the game encourages players to engage deeply with its mechanics and world.

## 2. Core Gameplay 

In a game designed for an audience already familiar with platformer mechanics (assuming teachers and other students already know the mechanics), the introduction of gameplay elements
can be more subtle, relying on environmental cues and player curiosity rather than explicit instructions. This approach can enhance immersion and encourage a sense of discovery.
Movement and Exploration

Mechanic Introduction: The game starts with a straightforward path, encouraging players to naturally explore movement options—running, jumping, and crouching—without overt instructions.
Justification: Assuming familiarity with platformers, players are expected to experiment with controls. This method respects the player's intelligence and previous gaming experiences,
allowing for a seamless entry into the game's world.

Melee Combat Introduction (Staff Acquisition)
Mechanic Introduction: The staff is placed along the player's path, with its acquisition seamlessly integrated into the game flow. The appearance of an easily defeatable enemy shortly
afterward serves as a natural prompt to use the new weapon.
Justification: Placing the staff in the player's path with an immediate opportunity to use it encourages learning through action. This method capitalizes on the player's curiosity
and inclination to experiment, facilitating a smooth introduction to combat mechanics.

Environmental Navigation (Acid Pool)
Mechanic Introduction: The acid pool presents an obvious hazard. The game design encourages players to jump over it, using platform placement and spacing to suggest this action implicitly.
Justification: By presenting an obstacle that interrupts the player's path, the design relies on the player's instinct to avoid danger and find a way around. This approach to teaching
through environmental design is intuitive and respects the player's ability to problem-solve.

Ranged Combat Introduction (Gun Acquisition)
Mechanic Introduction: After overcoming a series of obstacles and enemies with the staff, the player finds a gun placed in a manner that suggests its importance. The presence of
enemies out of melee range naturally encourages experimenting with the gun.
Justification: Introducing the gun after the melee weapon highlights the game's depth and the need for varied combat strategies. This placement, followed by the immediate necessity
to use it, teaches its utility in an organic, unforced way, emphasizing learning through direct engagement with the game world.

### 2.1. Checkpoints

### 2.2. Weapon Pickup (Staff)

### 2.3. Acid

### 2.4. Moving Platforms

### 2.5. Health Pickups

### 2.6. Stompers

### 2.7. Spitters

### 2.8. Weapon Pickup (Gun)

### 2.9. Keys

### 2.10. Spikes

### 2.11. Passthrough Platforms

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

DocImages/Diagram.png

## 4. Iterative Design 
Looking back at the crunch to finish my game assignment, I definitely wasn't fully committed. I jumped in late and, in a rush to cross the finish line, ended up missing a couple of key
pieces—namely, the hitpoint indicator and the key collection feedback. Honestly, I was banking on the provided required prefabs. My thought process was pretty much, 'If it’s required,
then let's only stick with it.' But, as it turns out, not using the optional prefabs made my game pretty basic. Also no UI elements are working makes it look worse.

I didn’t add instructions or visual cues for navigation and combat because I figured, 'Hey, we’re all gamers here, right? We know what we’re doing.' But, missing out on those UI elements
meant the game lost some of its potential to be intuitive and engaging. Not having a clear indication of health or how many keys you’ve got really takes away from the gameplay experience.
And yeah, that’s on me.

This whole experience was a bit of a wake-up call. It’s made me see how important it is to manage my time better and not underestimate the work that goes into even the simplest of features.
If I had started earlier or planned my workflow better, maybe I could have caught these issues sooner.

Going forward, I’m taking this as a learning curve. Next time, I’ll dive into the project with a better plan and respect for the iterative design process. I’ll make sure to test and refine
each element, especially the ones that seem minor but massively impact the player's experience. And maybe, just maybe, I’ll give myself enough time to actually enjoy the creative process
instead of racing against the clock.

So, yeah, not the smoothest project I’ve ever done, but definitely one I’ve learned a lot from.


