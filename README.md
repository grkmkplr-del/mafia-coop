# Mafia: The City of Lost Heaven: Co-op

> 🚧 **Work in progress.** The mod is under active development. No public build is available yet.

A story co-op mod for *Mafia: The City of Lost Heaven* (2002). The host plays the story as Tommy; the second player joins the same mission and shares the same world: the same NPCs, cars, traffic, pedestrians and police. Fight together, drive together, ride along, retry together.

**Current build:** 0.320 · **Patch notes:** [CHANGELOG.md](CHANGELOG.md)

---

## What the mod does

| Feature | Status |
|---|---|
| See the other player (movement, full animation, weapon in hand) | ✅ Working |
| Lobby: Host/Join Game in the main menu, New Game and Load Game together | ✅ Working |
| Cutscenes together, skipped only when both press skip | ✅ Working |
| Mission sync: host runs the mission, client follows (objectives, cutscenes, world state) | 🔧 In progress |
| Mission NPCs synced (movement, animation, health, death) | ✅ Working |
| Combat: both players can hit enemies, enemies target both players | ✅ Working |
| Shared game over and Retry | ✅ Working |
| World items: shared ground weapons and pickups, doors | ✅ Working |
| Throwing weapons to each other | ✅ Working |
| Weapon sharing between players | ✅ Working |
| Cars: driving, damage, locks and picklock synced | ✅ Working |
| Riding as passenger | ✅ Working |
| Own car for the second player in missions | ✅ Working |
| Enemy chase cars synced | ✅ Working |
| Moving between places together (garage, city) | ✅ Working |
| Mission dialogues: subtitles and conversations for both players | ✅ Working |
| Pause menu does not pause the game | ✅ Working |
| Name and health over the other player's head, other player on the map | 🔧 New, being tested |
| Separate save folder for co-op games | 🔧 New, being tested |
| Traffic mirrored, stealing cars, pulling drivers out | ✅ Working |
| Street pedestrians mirrored (same people, same skins, same deaths) | ✅ Working |
| Police arrest either player, shared Retry, police cops and roadblocks synced | ✅ Working |
| Police reacting to the second player's crimes and drawn weapons | ✅ Working |
| Mission checkpoints: the game waits for both players | ✅ Working |
| Story played together up to the race mission, without problems | ✅ Working |
| Race mission: only the host's race counts (see below) | ✅ Working |
| Dogs synced | 🔧 New, being tested |
| Full story campaign in co-op | 🔧 In progress |
| Playing over LAN / internet (join by IP) | 🔧 Built, not tested yet |

### In detail

- **Lobby.** A "Host/Join Game" option in the main menu: the host creates the game, the other player joins by IP. Starting a New Game or loading a save in the lobby starts it for both.
- **Cutscenes together.** Both players watch each cutscene at the same time; it is skipped only when both press skip.
- **Two players, one mission.** The host plays the story and leads the mission. The second player joins the same mission and sees the same objectives, cutscenes and changes in the world. *(In progress.)*
- **Players see each other.** Movement, turning and every animation of the other player, with the weapon in their hand.
- **Mission characters** (allies and enemies) move, animate, take damage and die the same way for both players.
- **Combat.** Both players can hit enemies and allies; enemies notice, target and damage both players. Allies' health bars are shown for both.
- **Game over and Retry.** A failed mission, a team wipe or an arrest ends the mission for both, and Retry restarts both together.
- **World items.** Weapons a mission hands out can be taken by both players, so nobody goes in unarmed. Weapons dropped during play exist once: whoever takes one, it is gone for the other. Doors are shared.
- **Weapon sharing.** Throw a weapon to the other player and they can pick it up and use it; players can share weapons with each other during a mission.
- **Cars.** Either player can drive; the other sees the car move, crash and take damage the same way. Car locks and picklocking are shared. Garage cars included.
- **Passengers.** Ride along while the other player drives, and get out while the engine is running.
- **Own mission car.** When a mission puts you in a car, the second player gets their own copy beside the host's. Enemy chase cars are the same for both.
- **Dialogues.** Both players see the subtitles of what characters say; during conversations the second player stands next to the host.
- **No pause.** Opening the ESC menu does not stop the game for the other player.
- **Co-op HUD** *(being tested)*. The other player's name and health over their head, and their position on the TAB map.
- **Checkpoints.** Either player can reach a mission checkpoint first; the game waits until both are there.
- **Race mission.** Only the host's race and lap times count: the host has to finish first to win. The second player gets their own race car and can drive around the track and race the other cars on their own, without lap times. After the race both players move on together.
- **Handy keys.** F10 jumps to the other player (with your car), F3 lets the host restart the mission.
- **Moving between places.** When a mission moves on to a new place, the game waits until both players are at the exit, and your car comes along.
- **Traffic.** City traffic and car colors are the same for both. Steal a car or pull a driver out, and the other player sees it happen.
- **Pedestrians.** The same people on the streets for both players, with the same looks, the same reactions and the same deaths.
- **Police.** Cops, police cars and roadblocks are the same for both players. The police react to the second player's crimes and drawn weapons and can arrest either player; the second player sees the handcuff icon and the crime text. Both players can fight and kill cops.

## Current limitations

- **Tested on one PC so far.** Joining by IP is built, but every test so far ran two copies of the game on the same computer. Playing over the internet may need the host to open a port on the router.
- Built for the Steam version of *Mafia* (app 40990). Other versions are not supported yet; the mod checks the game build and stays off on any other version.
- Race mission: the second player's race does not count, only the host's.
- Known issues are listed per version in the [patch notes](CHANGELOG.md).

## Screenshots & video

*Coming soon.*

<!-- ![Gameplay](docs/screenshot1.png) -->

## Availability

The source code is **not public yet**. It is kept private while development continues and will be released under the MIT license once the mod reaches a stable, playable state.

Watch ⭐ / 👁 this repository to get notified about releases.

## Feedback

Questions and suggestions are welcome in [Issues](../../issues).

## License

© 2026 Görkem Köprülü. **All rights reserved** until the public release.

*Not affiliated with 2K Games, Illusion Softworks or Hangar 13. Mafia is a trademark of its respective owners. No game files are included.*
