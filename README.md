# Hytale — Goblin Circus Raid Concept

**Status:** Concept / work in progress - **not yet built in-game**. The screenshots below show early blockouts, sketches, and references, not a finished or playable raid.

<img width="1760" height="990" alt="circus-entrance-blockout" src="https://github.com/user-attachments/assets/17ee20f9-e203-4bb1-9fd6-f7207e889982" />

The goblins run a circus powered by dark magic. The player receives an invitation and goes to investigate. What initially looks like a normal circus quickly turns into a raid-style dungeon with puzzles, boss fights, Magical Devices, and a mysterious Fog.

I wanted to try something different from a more traditional Hytale dungeon: encounters that are about more than just fighting enemies, but are still doable as a solo player.

## Contents

- [Reason and idea](#reason-and-idea)
- [The circus and the overall flow](#the-circus-and-the-overall-flow)
- [Encounter 1 — Opening Encounter](#encounter-1--opening-encounter)
- [Jump & Puzzle Section](#jump--puzzle-section)
- [The Wheel](#the-wheel)
- [Encounter 2 — Haunted Mansion](#encounter-2--haunted-mansion)
- [Encounter 3 — Escape Room](#encounter-3--escape-room)
- [Encounter 4 — Mirror Magician](#encounter-4--mirror-magician)
- [Encounter 5 — The Grand Strongman](#encounter-5--the-grand-strongman)
- [Encounter 6 — The Fog Beast](#encounter-6--the-fog-beast)
- [Final Encounter — The Director](#final-encounter--the-director)
- [Solo play, scaling, and replayability](#solo-play-scaling-and-replayability)
- [TL;DR](#tldr)
- [Project status and image references](#project-status-and-image-references)

## Reason and Idea

I love *Destiny*. Its raids are some of the coolest things I have seen in games. They are grand, challenging, and, most importantly, diverse. They are never only combat-focused, and the encounters require players to figure out mechanics and work together. Day One Raid Races are a big part of what makes them special to me.

After working on my Chapter 1 dungeon, I started thinking about what a raid-style goblin dungeon in Hytale could look like.

Obviously, I can't force a Hytale dungeon to be completed only by multiple people. The puzzles and encounters need to be possible in single-player too. I still wanted to explore how mechanics-based encounters could work in Hytale, perhaps even in its story/adventure content.

**Visual inspiration from Destiny (reference images, not my own work):**

<img width="1760" height="990" alt="destiny-raid-reference-01" src="https://github.com/user-attachments/assets/daf63c77-ceea-4f27-9ea1-2106166ef415" />

<img width="1600" height="900" alt="destiny-raid-reference-02" src="https://github.com/user-attachments/assets/ce4ca6e8-27ab-40c6-a332-19c9be3ba69a" />

<img width="1920" height="1080" alt="destiny-deep-stone-crypt-layout-reference" src="https://github.com/user-attachments/assets/34cd6e91-c4ee-4bb7-90d8-7ae674fb899d" />

## The Circus and the Overall Flow

The goblins have their own circus and dark magic. The first area should look like a fairly normal circus with a big tent in the center, inviting players to check it out.

<img width="1760" height="990" alt="circus-grounds-blockout" src="https://github.com/user-attachments/assets/58324aeb-dcaa-4379-af9a-5072a5487223" />


The intended overall flow is:

```text
Opening Encounter
       ↓
Jump & Puzzle Section
       ↓
The Wheel
       ↓
2 of 4 possible encounters
(ideally 1 mechanics-based encounter + 1 boss fight)
       ↓
The Fog Beast
       ↓
The Director (Final Boss)
```

The Wheel is the main replayability idea: rather than completing all four middle encounters, players would only do two per run. The exact selection and balancing still need testing.

## Encounter 1 — Opening Encounter

The players enter the big tent and move toward the center stage. The Director sits on his throne and commands the goblins to attack.

<img width="1760" height="990" alt="opening-encounter-stage" src="https://github.com/user-attachments/assets/192b2248-74eb-481e-b20b-e5606490edc7" />

Different enemies swarm from **three gates** in waves. I don't want the encounter to overwhelm players, so enemy spawns should account for how many enemies are still alive.

Players have to enter the newly opened areas and destroy a portal or device that summons the enemies. After destroying one, they are forced back into the center. A stronger enemy spawns at each remaining device.

After all three devices are destroyed, the Director becomes enraged and joins the battle himself. This is supposed to be a more casual opening boss fight.

For now, I used the Feastmaster as a placeholder, but I imagine the Director as a skinnier, longer creature. The boss stays or floats near the center of the arena, summons some enemies, and could use rotating flames to make the fight a little harder.

<img width="1760" height="990" alt="opening-encounter-arena" src="https://github.com/user-attachments/assets/5ea2a3fc-c80f-4271-97a8-2c20223cad36" />

When defeated, the Director explodes and opens the marked floor area, revealing a big drop with a portal at the bottom. A knockback effect prevents players from immediately falling into the hole. A reward chest spawns, and the encounter is complete.

## Jump & Puzzle Section

Players jump into the hole and get teleported into what feels like the underbelly of the circus.

This section is a shorter jumping and puzzle sequence. Goblins throw things at players while they navigate the area. Players need to find **two buttons** to open a gate, then continue through more jumping sections until they reach a theatre containing a large spinning wheel.

<img width="1760" height="1021" alt="jumping-puzzle-section" src="https://github.com/user-attachments/assets/063941f4-409a-424f-9095-36e703b6c4f6" />

## The Wheel

I would normally design a raid more linearly, but a spinning Wheel fits the circus theme and could add randomness and replayability.

<img width="1760" height="990" alt="wheel-room" src="https://github.com/user-attachments/assets/8f75395c-321f-4b22-9ae4-d7c6f565ddfe" />

A button beneath the Wheel starts it spinning. Once it stops, it selects one of four encounters and opens the corresponding curtain.

<img width="1760" height="990" alt="wheel-four-encounters" src="https://github.com/user-attachments/assets/ab5e8b06-27ab-4c46-91a4-68ba4ea6afbb" />

**Current idea:** Players complete **two of the four** available encounters per run. Ideally, the selection always includes one mechanics-based encounter and one boss fight.

The middle encounters also introduce mechanics that return during the final boss. Since players might not see two of them, I need to make sure the final fight remains understandable regardless of which encounters the Wheel picked.

This is still an idea that would need iteration and actual playtesting.

## Encounter 2 — Haunted Mansion

**Type:** Mechanics-based encounter / timed traversal

Players move through twisted rooms with moving platforms and rotating elements, then enter a Haunted Mansion and board a train. The train moves through the haunted house but stops three times because something is blocking the tracks.

<img width="1280" height="720" alt="haunted-mansion-train-reference" src="https://github.com/user-attachments/assets/99b643f7-c6fc-498c-8c52-fe289c4c67d4" />

### Stop 1 — Learn the Magical Devices

The first stop introduces the carrying mechanic. Two lights need to be activated before the train can move again.

<img width="1760" height="990" alt="haunted-mansion-stop-one" src="https://github.com/user-attachments/assets/96f02c41-a004-4e07-958c-5c7ccfe4f1a5" />

There are four accessible rooms: two containing Magical Devices and two containing slots where they need to be placed. Players find a device, destroy or release it, pick it up, and carry it to an open slot. Lines help guide them toward the lights.

A timer starts whenever the train stops and resets whenever a light is powered on. If it runs out, a huge, blobby monster runs along the tracks and destroys the train, causing a wipe. The monster cannot be damaged or killed.

Poltergeists attack while players explore. Their number should scale down for solo players, and the rooms themselves should use moving and rotating elements to make navigation interesting.

Once both lights are on, the timer disappears and the train moves again.

### Stop 2 — Changing Portals

The second stop works similarly, but now **three lights** must be activated.

This time, Magical Devices cannot simply be placed into their final slots. Some devices first need to activate doors and unlock new passages to reach the remaining devices.

Portals move players between rooms and change their destinations after lights are activated. The timer is still there to create pressure. I also considered some gravity-defying elements, but that might be a bit too much.

### Stop 3 — Descending Tower

The train stops one final time, and after a short delay, the tracks begin descending through a tower. The unkillable monster (possibly the Fog) appears above and slowly follows it downward.

<img width="1760" height="990" alt="haunted-mansion-descending-tower" src="https://github.com/user-attachments/assets/b8e70695-364b-4666-a8b8-abe1ca20c7bb" />

Players jump out of the train into adjacent rooms and activate multiple lights before the train reaches the portal at the bottom. The portal sends the train back to the top. The side rooms should gradually lead players downward so they can stay near the train. Goblins and poltergeists keep attacking.

I like the idea of scaling the required number of Magical Devices and lights with player count. This final stop should be hectic for a team, but still possible solo.

<img width="2048" height="1152" alt="haunted-mansion-tower-path-layout" src="https://github.com/user-attachments/assets/314b20d7-550e-4438-8f84-dc3e7d6b435c" />

*Very rough tower layout: the side paths should generally trend downwards.*

The descent should probably be relatively slow on normal difficulty. Hard Mode could speed it up.

Once all lights are activated, the monster disappears, the train finishes its ride, and a chest spawns. Players can return to the Wheel.

## Encounter 3 — Escape Room

**Type:** Room-swapping puzzle / moving Fog hazard

Players enter a set of rooms that can change positions. They have to connect Magical Devices to the center room while avoiding a mysterious Fog that moves from room to room.

<img width="1424" height="1144" alt="escape-room-overview" src="https://github.com/user-attachments/assets/9e159c09-8d59-46f5-9409-334887e55d21" />

The encounter begins in the bottom-middle starting room. Destroying an object (possibly a Haunted Vase) starts the encounter and releases the Fog into one of the marked rooms.

### Layout and Goal

The room layout is roughly:

```text
X E X
X G X
X S X
```

- **S:** Starting Room
- **G:** Center / goal room, containing three lights
- **E:** Exit
- **X:** Movable rooms

Players need to activate all **three lights** in the G-Room. Each room has a different power connection, and the rooms must be rearranged to create a connection between a Magical Device and the center.

<img width="1056" height="1115" alt="escape-room-fog-rooms" src="https://github.com/user-attachments/assets/1d08c1f0-9db8-4211-80f1-38d24359e4f0" />

### Swapping Rooms

A **Portal Guardian** periodically spawns in an accessible room. Killing it opens a portal in the Starting Room, or another safe room if the Starting Room is covered by Fog.

Entering the portal takes players to a control room where they can **swap two rooms**, but not rotate them. After one swap, they are sent back. A UI may be easier to implement, but I like the idea of showing players an overview of the actual room layout.

<img width="1760" height="990" alt="escape-room-control-room" src="https://github.com/user-attachments/assets/383ccc57-ae30-497d-85bf-2a5478a8b076" />

All eight movable rooms have different connection types — straight, corner, or T-junction. The center G-Room can be swapped as well. I would rather hand-design three or four valid starting layouts and select one randomly than generate completely random, potentially impossible puzzles.

<img width="1288" height="1155" alt="escape-room-power-connections" src="https://github.com/user-attachments/assets/d3088530-f849-4674-b33d-f105603ad2d6" />

When one light is activated, that Magical Device disappears and a new one spawns in another room. The completed light stays on.

### The Fog

The Fog Core moves between rooms following a **fixed, learnable sequence based on symbols**, even if the rooms themselves have been shuffled. Each move leaves behind **Fog Residue**, which also makes rooms dangerous. Foggy rooms damage and heavily slow players instead of simply blocking them with an invisible wall or instant-kill barrier.

The Fog is attached to its room when that room gets swapped.

<img width="1288" height="1155" alt="escape-room-room-symbols" src="https://github.com/user-attachments/assets/d5d5075f-fe32-4796-9aca-0e2115de5348" />

An example sequence could be:

`Moon → Diamond → Tower → Star → Crown → Blade → Eye → Sun`

The Fog Core avoids the G-Room until the end of its cycle.

To clear **Fog Residue**, players swap a Magical Device room next to the affected room. If they instead put a Magical Device next to the **Fog Core**, it accelerates the Core's next jump. The Core itself cannot be removed. These checks happen when a room swap takes place.

If all eight movable rooms become foggy and the team dies, the encounter ends in a wipe.

### Difficulty and Completion

I would probably start by testing a Fog jump every **75–90 seconds**. Enemy spawns and potentially the Fog timer need to scale with player count. Solo players cannot have the same pressure as a coordinated group.

When all three center lights have been activated, the Fog disappears, the exit opens, and the players receive a chest and a way back to the Wheel.

## Encounter 4 — Mirror Magician

**Type:** Boss fight / identifying illusions

This is intended to be a more straightforward boss encounter with a few immunity phases. The arena is open, with a few different elevations.

The boss starts immune and summons illusions around the arena. The illusions periodically cast spells, such as AoE explosions. Players have to find and destroy the **correct illusion**, identified either by a visual difference or by casting a different spell.

The correct illusion drops a **Magical Device**. Inserting it into a slot makes the boss vulnerable for a limited damage phase. I currently prefer a timed phase rather than ending it after a fixed percentage of HP, because it allows players to burst the boss down.

Destroying a wrong illusion still drops a device, but this one is faulty. Using it causes parts of the arena to fill with Fog for a while and summons additional goblins. The boss also summons goblins while immune.

When defeated, the boss drops a chest and players return to the Wheel.

**Design note:** This is probably my weakest encounter concept right now and would need more iteration.

## Encounter 5 — The Grand Strongman

**Type:** Boss fight / positioning and baiting attacks

The arena is circular and contains several marked zones. The boss is initially immune to damage and constantly chases players using melee attacks and a charge.

<img width="1760" height="990" alt="grand-strongman-arena" src="https://github.com/user-attachments/assets/5b894209-e618-4f14-9e30-02b12586145a" />

Players have to **bait the boss into charging into a structure**. On impact, a Magical Device drops and the boss is briefly stunned, but still immune.

Players take that device to a highlighted zone, lure the boss inside it, and insert the device. The zone shocks and stuns him, opening a longer damage phase. When the boss becomes immune again, players repeat the process.

<img width="1760" height="990" alt="grand-strongman-shock-zones" src="https://github.com/user-attachments/assets/23880db1-cbdb-4f74-8520-514556b9b3f1" />

*The shock zones would probably have a pedestal in the center and some kind of visual range indicator.*

After each damage phase, the previously used zone becomes infested with Fog, forcing players to pick a new position next time.

The structures containing Magical Devices should probably be visible from the start, rather than appearing randomly. I think that would be clearer to the player.

Once the boss is defeated, the Fog disappears, a chest spawns, and the players return to the Wheel.

### Returning to the Wheel

After completing two of the four selected encounters, the Wheel opens the final door. A short jumping section leads to the next stage.

## Encounter 6 — The Fog Beast

**Type:** Mandatory boss fight / floodlights and immunity phases

This is the last encounter before the final boss, and it should reinforce the mechanics the player has already seen. The Fog has appeared throughout the dungeon, so I thought it would be fitting to finally fight the creature behind it.

The fight takes place in a theatre. Goblins watch while the players fight the Fog Beast on stage.

<img width="1760" height="990" alt="fog-beast-stage" src="https://github.com/user-attachments/assets/b690288f-1a44-46e6-837e-27fe9715109d" />

### The Fight

The giant Fog monster escapes from a magical prison on stage. Lights are shining onto it; when it breaks free, those lights go out. This should hint to players that **light is important**.

The boss starts immune, charges across the stage, and leaves small Fog clouds that disappear over time.

Players have to collect Magical Devices, climb up to the platforms above the stage, and activate **two floodlights**. The floodlights follow the boss, stun it, and open a damage phase.

<img width="1760" height="990" alt="fog-beast-stage-front" src="https://github.com/user-attachments/assets/9618fb37-be8d-4568-9a4a-8c95f7a754b9" />

*The stage could contain props and different elevations. Backstage routes on either side give players space, but should not be completely safe places to stay forever.*

<img width="1760" height="990" alt="fog-beast-floodlight-platforms" src="https://github.com/user-attachments/assets/a1701ecd-02b5-4026-8c4c-6ff93780fb31" />

After a while, the boss destroys the lights, becomes immune again, and the process repeats. Its attacks could include charging over players, clawing at them, and spitting Fog.

### Visual Direction

I imagine something with the unsettling, dark shape of No-Face from *Spirited Away*, but adapted to the Fog creature and circus theme.

<img width="415" height="738" alt="fog-beast-no-face-reference" src="https://github.com/user-attachments/assets/e6b7fc75-692e-41bc-a3a6-1f68bb70f961" />

*Visual reference only — not original project artwork.*

The stage should have enough props and obstacles to break up the space without making the arena too small for the boss.

### Hard Mode Ideas

- If players take too long to stun the boss, it becomes enraged and more aggressive.
- Hard Mode could require **three Magical Devices / floodlights** instead of two.

On defeat, a chest appears. I also like the idea of a smaller version of the creature escaping toward the next encounter.

## Final Encounter — The Director

**Type:** Final boss / illusions, Fog, room mechanics, floodlights, Last Stand

I wanted the Circus Director to be the final boss, not the Fog Beast. The idea is to reuse mechanics players have been learning throughout the raid, but combine them in one larger fight.

The final arena could be a circus tent floating in the Void, connected by a path of floating debris and broken blocks.

<img width="1760" height="990" alt="director-floating-tent" src="https://github.com/user-attachments/assets/9d8cda0e-135a-4fa4-8160-bf24eca6d8b3" />

### Phase 1 — The Real Director

The Director creates multiple illusions and becomes immune. The illusions cast spells that cause AoE explosions or move platforms around the arena.

The real Director has a small amount of Fog coming from him. Players have to identify and attack the real one, which breaks his shield and leaves him vulnerable for a set time. The mechanic repeats until the phase ends.

### Phase 2 — Eight Rooms

The Director raises walls inside the arena, creating **eight rooms around the center**. He remains in the middle and begins leaking Fog. A symbol appears above his head.

<img width="868" height="867" alt="director-phase-two-layout" src="https://github.com/user-attachments/assets/dbc9a0b0-696b-480a-ac89-16bef19fa4c4" />

The Fog slowly damages players in the center and pushes them toward the surrounding rooms.

Players have to find the **correct room** for the displayed symbol and defeat the Fog Effigy inside. The Effigy reveals an empty Magical Device slot.

A **Portal Guardian** occupies another room. Killing it opens a portal to an area where players can collect a Magical Device. When they bring it back and insert it into the slot, the Fog stops leaking and the Director becomes vulnerable.

### Phase 3 — Shattered Arena

After Phase 2, the Director releases a shockwave, destroys the walls, and shatters the arena into floating debris.

<img width="1760" height="990" alt="director-phase-three-arena" src="https://github.com/user-attachments/assets/ac0a3b27-6f1c-4464-8e73-ac5df88659ba" />

The Director floats in the center and fires Fog projectiles at players or positions around the arena.

Players need to collect **two Magical Devices** and power floating floodlights. Once both are active, the boss falls down, becomes stunned, and can be damaged. Repeat until defeated.

### Last Stand

When the Director reaches zero HP, he enters a final Last Stand instead of dying immediately. Visually, he begins pulling in the Fog, and the safe area around him shrinks quickly.

<img width="1760" height="990" alt="director-last-stand-fog" src="https://github.com/user-attachments/assets/17701314-16ac-4343-ab97-a11e5bfcccec" />

Players have to finish him before the Fog deals enough damage to kill everyone.

When defeated, the Director disappears and leaves a large loot chest.

## Solo Play, Scaling, and Replayability

I want the entire raid to remain possible **in single-player**, even though the encounter design takes inspiration from multiplayer raids.

The core mechanics should remain the same, but a few things could scale with player count:

- **Enemy count:** fewer goblins and poltergeists when playing solo.
- **Enemy health:** adjust where needed so solo play does not become exhausting.
- **Timers:** allow enough time for one player to complete carrying and navigation mechanics.
- **Magical Devices and lights:** some encounters could require more devices for larger groups.
- **Hard Mode:** shorter timers, faster hazards, or additional mechanics such as more floodlights.

The Wheel should also add replayability by selecting only two of the four middle encounters. This is still a concept, though, and balancing it properly would require actual playtesting. I especially need to make sure players understand the final boss even if they haven't seen every mechanic during a particular run.

## TL;DR

**Overall progression:**

`Opening Encounter → The Wheel → 2 of 4 encounters → The Fog Beast → The Director`

| Encounter | Main idea |
| --- | --- |
| **Opening Encounter** | Destroy three enemy-summoning devices, defeat an introductory version of the Director, and drop into the circus underbelly. |
| **The Wheel** | Randomly choose two of four middle encounters, preferably one puzzle and one boss fight. |
| **Haunted Mansion** | Ride a train, activate lights with Magical Devices, and escape a timed wipe monster across three stops. |
| **Escape Room** | Swap eight rooms to connect power to the center while a learnable Fog Core spreads Fog Residue. |
| **Mirror Magician** | Identify the correct illusion to obtain a working Magical Device and break the boss's immunity. |
| **Grand Strongman** | Bait a charge, collect a Magical Device, and shock the boss in marked zones that later fill with Fog. |
| **Fog Beast** | Activate floodlights above a theatre stage to stun an immune Fog monster. |
| **Director — Phase 1** | Find the real Director among his illusions. |
| **Director — Phase 2** | Solve a symbol-based room mechanic and bring a Magical Device back to break immunity. |
| **Director — Phase 3** | Activate floating floodlights in a shattered arena. |
| **Director — Last Stand** | Finish the boss before the incoming Fog closes the arena. |

## Project Status and Image References

This repository documents a **design concept**, not a finished Hytale map or mod. The in-game screenshots are early blockouts, and some mechanics are placeholders or ideas that still require implementation and playtesting. The encounter order, balance, timings, visuals, and even some abilities may change.

The following images are **external inspiration/reference images**, not artwork or screenshots created by me:

- Destiny raid imagery and the Deep Stone Crypt encounter reference.
- The haunted train reference photograph.
- No-Face from *Spirited Away*.

The other diagrams, layouts, and blockout screenshots are included to explain my own encounter concepts. Third-party imagery is shown solely as a reference; rights remain with the respective owners. If reusing or publicly distributing these reference images, check whether you have permission to do so, or replace them with links to their original sources.
