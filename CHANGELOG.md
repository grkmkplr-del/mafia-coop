# Patch notes

Development history of the Mafia co-op mod. Every build was tested with two copies of the game running side by side.

---

## 0.214 – 0.218 (2026-11-14): co-op HUD, co-op saves (new, being tested)
- The other player's name and health are shown over their head (green / yellow / red), up to 150 m away.
- The other player is shown on the TAB map as a green arrow with their name.
- Co-op games keep their own save folder, separate from your single-player saves.
- Fixed the second player missing the host's story events when a new mission starts.
- Before a mid-mission cutscene the game waits until both players are close together.

## 0.207 – 0.213 (2026-11-14): dialogues, Retry with your own car
- The second player now sees the subtitles of what characters say during missions.
- During conversations the second player stands next to the host and both watch the talk together.
- After a Retry each player is back in their own car.
- Fixed a crash at the start of a conversation.
- Fixed a traffic car sometimes missing on the second player's side.

## 0.201 – 0.206 (2026-11-14): garage exit, pause menu
- Both players can leave the garage, each in their own car or together in one car.
- **ESC no longer pauses the game:** the world keeps running while one player is in the menu, as it should in co-op.
- The second player gets their own car back after a Retry in the city.
- The second player no longer gets a game-over menu: they wait on a dark screen until the host chooses Retry.
- Fixed a crash at the garage exit.

## 0.196 – 0.200 (2026-11-14): moving between places together
- When a mission moves you to a new place (for example from the garage into the city), the game waits at the exit until both players are there.
- The car you drove or rode in comes along to the new place for both players.
- Fixed a crash after moving from the garage into the city.
- Fixed a frozen copy of the other player left floating after a scene change.

## 0.188 – 0.195 (2026-11-14): Load Game together, police fights
- **Load Game together:** the host loads a save and the second player gets the same save and starts in the same mission.
- The second player can now shoot and kill cops who got out of police cars; dead cops fall for both players.
- Fixed a crash on Retry and a crash while riding along.
- Allies no longer climb into the second player's car on the host's side.

## 0.177 – 0.187 (2026-11-14): own car, chase cars, Retry fixes
- **Own mission car:** when a mission puts you in a car, the second player gets their own copy right beside the host's and drives it.
- Enemy chase cars are the same for both players.
- Fixed the second player's game hanging after a Retry.
- Fixed leftover copies of the players standing around after a Retry.
- When the host dies, the second player's mission restarts together with the host's.

## 0.174 – 0.176 (2026-11-14): stability
- Fixed a crash at the end-of-mission cutscene.
- The HUD comes back for the second player after a Retry.
- Fixed the first mission's start: both players now see its opening cutscene, and the host drives when a mission starts with both players in a car.

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
