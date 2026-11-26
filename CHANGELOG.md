# Patch notes

Development history of the Mafia co-op mod. Every build was tested with two copies of the game running side by side.

---

## 0.514 – 0.549 (2026-11-26): all missions fixed, automatic port (UPnP)
**All missions have been tested and fixed: the whole story is playable together.**

**Next step:** a test over the internet with a second PC. The mod will be shared right after that test.

Today's changes:
- **Automatic port (UPnP):** the host can now play with or without opening a port by hand. With "Auto port (UPnP)" on, the mod asks the router to open the port and shows the IP the other player has to enter. If that is not possible, the lobby says why (no router, no public IP, …).
- **Ready for release:** the game runs in full screen with its own display settings, logs are kept small, and an install package with instructions was put together.
- Mission timers (for example in the motel mission) now run the same for both players.
- Race: the second player's camera no longer zooms in after a Retry.
- Fixed civilians on the ship raising the alarm too early for the second player.
- Enemies aim a bit better; the plane at the airport has more health, and it no longer grows with every restart.
- The second player starts empty-handed after a load, like the host.
- The second player's deaths right after a scene change are no longer missed.
- Some opening cutscenes cannot be skipped in their first seconds, so both players start together.
- Fixes in the villa, Salieri's bar garage and the bar cutscenes after a Retry.

## 0.439 – 0.513 (2026-11-21 – 2026-11-25): every mission tested and playable
**All missions have been fully tested and the whole story is playable together.** Small bugs and fixes are left in the loading parts of 3 – 5 missions.

**Not tested over the internet yet:** so far both games ran on one PC (localhost). Tests from other PCs, with the host's port opened, are coming soon.

Main changes:
- **Enemies have more health in co-op** (about twice as much; a bit less in the last mission), so missions stay a challenge with two players.
- Enemies now hear the second player's shots and react to them, and they react faster.
- Pedestrians, enemies and trams are fully synced. Police on foot are only partly synced: some foot cops may not look the same in both games.
- The second player's health and weapons now carry over correctly through mission changes, Retries and the gun shop.
- Synced the crates in the truck missions, the drawbridges and the gun shop.
- The second player's car follows through every checkpoint, Retry and loaded save.
- Prison: both players are kept safe while dropping into the sewer; the sewer exit no longer gets stuck.
- Some opening cutscenes cannot be skipped in their first seconds, so both players start the fight at the same moment.
- Many crash fixes across the late missions.

## 0.371 – 0.438 (2026-11-19 – 2026-11-20): story playable up to "Crème de la Crème"
**The story can now be played together from the start up to the "Crème de la Crème" mission.** Only a few small issues are left in the earlier missions; fixing them should not take long.

Main changes:
- **Save system reworked:** the second player's weapons and health are now saved without problems and stay fully in sync, also across mission changes and Retries. The second player's car is kept with the save too.
- **Police:** cops in police cars, traffic police cars and roadblocks now match for both players; no more duplicate police cars or crowds of extra cops on the second player's side.
- Fixed the game slowing down to a few frames per second after several Retries.
- Fixed missing traffic for the second player at the restaurant.
- Fixed a common crash when quitting the game.
- Many missions needed their own co-op fixes (the villa, the garage fight, the truck chase, the restaurant, the traitor, the disguise on the ship, Vincenzo's bomb, the port chase); some of them took a lot of work.
- Many crash fixes around cars, allies getting in and out of cars, Retries and loaded saves.

## 0.321 – 0.370 (2026-11-17 – 2026-11-18): story playable up to "Visiting Rich People"
**The story can now be played together from the start up to the "Visiting Rich People" mission.** Fixes are ongoing.

Main changes:
- **In-game chat:** press T to type, Enter to send.
- **F6** shows the co-op keys (like F1 shows the objectives).
- **Saves keep both players:** mission autosaves are written for both, and the second player's own weapons and health come back after loading a save or a Retry.
- Wait messages ("Waiting for the other player", "Both players must be at the checkpoint", skip votes) now appear in the game's own HUD, and at the top of the screen during cutscenes.
- Cutscenes wait until the second player is close before they start.
- The second player's death is now always seen by the host, also outside the race.
- Race mission: the race panel (time, lap, position) is shown to the second player; if the second player dies, the race ends and both can Retry.
- Trams are the same for both players; more pedestrians in the city centre.
- During camera dialogues the second player stays next to the host and is released when the talk ends.
- Mission-specific fixes (Salieri's bar, Sarah, the hooligans, the barn, the truck ride, the airport).
- Many crash and freeze fixes around cutscenes, cars, Retries and mission changes.

## 0.296 – 0.320 (2026-11-16): the race mission
- The story can now be played together up to the race mission without problems.
- **Race mission:** only the host's race counts. The host has to finish first to win; the second player can drive around the track and race the other cars on their own, without lap times.
- The race cars move the same on the second player's side, and the second player gets their own race car beside the host's.
- After the race both players move on to the next mission together.
- **F3** also restarts the race; the race's pause menu no longer stops the game.
- The race's difficulty dialog is skipped (the game's default difficulty is kept).
- Fixed a crash after restarting the race and the second player's game hanging on "Please wait" after the race.

## 0.270 – 0.295 (2026-11-16): motel, rescuing Sam, dogs
- Dogs are the same for both players and both can fight them.
- Rescuing the wounded Sam: the host has to reach Sam himself; the game shows "Both players must be at the checkpoint" until both are there.
- The car at the Clark motel is parked at the pump for both players, also after skipping the cutscene.
- First-aid boxes on walls heal the second player too.
- A second co-op session in the same game (back to the menu, host again) works.
- Moving to the next mission is no longer missed by the second player.
- Fixed a duplicate "Front" door option on the other player's car.
- **F10** during a checkpoint wait puts you right next to the other player (on foot only).

## 0.244 – 0.269 (2026-11-15): story missions 1 – 3 together
- Played together from a New Game through the end of the first mission, into the taxi mission and Molotov Party.
- Cutscenes stay in sync across the first missions; a skip now counts only for the cutscene both players are watching.
- The intro video is skipped in co-op, so both games start the story together.
- **F10:** jump to the other player (with your car if you drive).
- When a cutscene moves the host somewhere else, the second player is brought along.
- Molotov Party: both players start in the mission car; the cars you have to wreck at Morello's garage take the same damage for both players.
- Cars Ralph teaches you to steal are learned by both players.
- Fixed getting into the other player's car, and getting back into a car after a loaded save.
- Fixed several crashes after mission changes, Retries and loaded saves.

## 0.219 – 0.243 (2026-11-15): checkpoints, enemies, Retry key
- Mission checkpoints work when the second player reaches them first; the game waits until both players are there.
- Enemies that arrive later in a mission can be hit by the second player; NPCs get the same weapons in their hands as on the host.
- Bodies no longer block bullets or movement on the second player's side.
- Ground weapons now also show indoors.
- **F3:** the host can restart the mission (Retry) at any time.
- Fixed black screens and freezes after cutscenes and Retries.

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
