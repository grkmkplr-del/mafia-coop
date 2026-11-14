# Patch notes

Development history of the Mafia co-op mod. Every build was tested with two copies of the game running side by side.

---

## 0.174 – 0.176 (2026-11-14): stability
- Fixed a crash at the end-of-mission cutscene.
- The HUD comes back for the second player after a Retry.
- Fixed the first mission's start: both players now see its opening cutscene, and the host drives when a mission starts with both players in a car.
- Known issue: the chase car in a mission is not synced yet.

## 0.155 – 0.173 (2026-11-13 – 2026-11-14): lobby and cutscenes together
- **New "Host/Join Game" option in the main menu.** The host enters a name and a port and creates the game; the other player joins with the host's IP and port.
- Starting a New Game from the host's lobby starts the game for both players together.
- Cutscenes start for both players at the same time and are skipped only when both press skip.
- Played together from the intro into the first mission; Retry works there too.
- Fixed several hangs and crashes around cutscenes and the first mission.

## 0.148 – 0.154 (2026-11-13): getting arrested as the second player
- The police can arrest the second player; the mission ends for both and Retry restarts both.
- The second player sees the handcuff icon and the crime text when the police are after them.
- Police cars and cops no longer vanish for the second player after a Retry.

## 0.145 – 0.147 (2026-11-13): police and the second player's crimes
- The host's police now learn about crimes committed by the second player.
- The police notice when the second player draws a weapon.

## 0.140 – 0.144 (2026-11-12): police pool and roadblocks
- Police roadblock cars look the same for both players.
- All cops of a police deploy are synced, not just the first ones.

## 0.124 – 0.139 (2026-11-12): arrest and police
- Getting arrested ends the mission for both players; Retry restarts both.
- Police cops and roadblock cars are the same for both players; police cars no longer vanish for the second player.
- Pedestrians shot by the second player die for both players.
- The second player's crimes raise the police alert for the host.

## 0.115 – 0.123 (2026-11-12): traffic drivers
- A driver pulled out of a car is the same person for both players and stays in sync.
- Either player can pull a driver out, and either player can kill him.

## 0.106 – 0.114 (2026-11-12): pedestrians
- Street pedestrians are the same for both players: same places, same skins.
- Pedestrians crouching, lying down or dying look the same for both.

## 0.87 – 0.105 (2026-11-12): traffic
- City traffic and car colors are the same for both players.
- Both players can steal traffic cars and pull drivers out; no duplicate cars.
- Either player can ride along in a car the other stole.
- Cars collide with mirrored traffic.
- Known issue: people can walk through mirrored traffic cars on the second player's side.

## 0.76 – 0.86 (2026-11-11 – 2026-11-12): passengers
- Ride along as a passenger while the other player drives, in any car including garage cars.
- Either player can drive with the other aboard.
- Passengers can get out while the engine is running.

## 0.56 – 0.75 (2026-11-10 – 2026-11-11): cars
- Either player can drive; the other sees the car move, crash and take damage the same way.
- Car locks and picklocking are shared.
- Driven cars are solid and cast shadows for the other player.

## 0.41 – 0.55 (2026-11-10): weapons, items, doors
- The other player's weapon is visible in their hand.
- Weapons a mission hands out can be taken by both players; dropped weapons can be taken by only one.
- Enemies killed by the second player can be looted.
- Doors are synced.
- "Waiting for host" screen while the mission restarts.

## 0.19 – 0.40 (2026-11-09): combat and mission flow
- The second player's bullets hit enemies and allies reliably.
- Allies' health bars shown for both players.
- Enemies see, target and damage the second player.
- Mission failure, game over and Retry work for both players; cutscenes no longer freeze.
- Team wipe: the mission ends when both players are down.

## 0.9 – 0.18 (2026-11-09): mission sync and NPCs
- The host runs the mission; the second player sees the same objectives, cutscenes and world changes.
- Mission characters move and animate the same way for both players.

## 0.4 – 0.8 (2026-11-09): seeing each other
- The two game copies connect.
- Each player sees the other walking, running and turning, with all animations.

## 0.1 – 0.3 (2026-11-09): first steps
- The mod loads safely: it checks the game version first and does nothing on an unknown build.
- Two copies of the game can run side by side in windows.
