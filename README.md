# Mafia: The City of Lost Heaven: Co-op

> 🚧 **Work in progress.** The mod is under active development. No public build is available yet.

A story co-op mod for *Mafia: The City of Lost Heaven* (2002). The host plays the story as Tommy; the second player joins the same mission and shares the same world: the same NPCs, cars, traffic, pedestrians and police. Fight together, drive together, ride along, retry together.

**All missions have been tested and fixed: the whole story is playable together.**

**Online play over the internet works.** Depending on the quality of the connection, small momentary sync glitches can happen.

**Current build:** 0.593 · **Patch notes:** [CHANGELOG.md](CHANGELOG.md)

---

## What the mod does

| Feature | Status |
|---|---|
| See the other player (movement, full animation, weapon in hand) | ✅ Working |
| Lobby: Host/Join Game in the main menu, New Game and Load Game together | ✅ Working |
| Cutscenes together, skipped only when both press skip | ✅ Working |
| Mission NPCs synced (movement, animation, health, death) | ✅ Working |
| Combat: both players can hit enemies, enemies target both players | 🟡 Mostly working |
| Throwing weapons to each other | ✅ Working |
| Weapon sharing between players | ✅ Working |
| Cars: driving, damage, locks and picklock synced | ✅ Working |
| Riding as passenger | ✅ Working |
| Moving between places together (garage, city) | ✅ Working |
| Mission dialogues: subtitles and conversations for both players | ✅ Working |
| Co-op saves: the second player's weapons and health are saved, fully in sync | ✅ Working |
| Pedestrians: fully synced | ✅ Working |
| Enemies: fully synced | ✅ Working |
| Police: partly synced (some foot cops may not look the same in both games) | 🟡 Partly synced |
| Police arrest either player, shared Retry, police cars and roadblocks synced | ✅ Working |
| Police reacting to the second player's crimes and drawn weapons | ✅ Working |
| Mission checkpoints: the game waits for both players | ✅ Working |
| In-game chat (T) | ✅ Working |
| Race mission: only the host's race counts (see below) | ✅ Working |
| Full story campaign in co-op: all missions tested and fixed | ✅ Working |
| Playing over LAN / internet: join by IP; the host opens a port by hand or lets the mod open it automatically (UPnP) | ✅ Working (small momentary sync glitches can happen, depending on the connection quality) |

### In detail

- **Lobby.** A "Host/Join Game" option in the main menu: the host creates the game, the other player joins by IP. Starting a New Game or loading a save in the lobby starts it for both.
- **Port or no port.** The host can open the game's port on the router by hand, or turn on "Auto port (UPnP)" in the lobby and let the mod open it; the lobby then shows the IP the other player has to enter.
- **Cutscenes together.** Both players watch each cutscene at the same time; it is skipped only when both press skip.
- **Players see each other.** Movement, turning and every animation of the other player, with the weapon in their hand.
- **Mission characters** (allies and enemies) move, animate, take damage and die the same way for both players.
- **Combat.** Both players can hit enemies and allies; enemies notice, target and damage both players. Allies' health bars are shown for both. The game's AI is fairly simple, so enemies sometimes take a moment longer to target the second player.
- **Weapon sharing.** Throw a weapon to the other player and they can pick it up and use it; players can share weapons with each other during a mission.
- **Cars.** Either player can drive; the other sees the car move, crash and take damage the same way. Car locks and picklocking are shared. Garage cars included.
- **Passengers.** Ride along while the other player drives, and get out while the engine is running.
- **Dialogues.** Both players see the subtitles of what characters say; during conversations the second player stands next to the host.
- **Saves.** Co-op games use their own save folder. The second player's weapons, health and car are saved with every save and come back after loading or a Retry, fully in sync with the host.
- **Tougher enemies.** Two players are stronger than one, so enemies have more health in co-op (about twice as much, a bit less in the last mission). Enemies also hear the second player's shots and react to them.
- **Mission by mission.** Every mission needs its own co-op fixes: scripted scenes, cars, allies and checkpoints all behave differently. Some missions needed a lot of fixes and took a lot of work.
- **Checkpoints.** Either player can reach a mission checkpoint first; the game waits until both are there.
- **Race mission.** Only the host's race and lap times count: the host has to finish first to win. The second player gets their own race car and can drive around the track and race the other cars on their own, without lap times. After the race both players move on together.
- **Connection info.** Ping and packet loss are shown in the bottom-right corner; if the other player is gone for 10 seconds, the game says the connection was lost.
- **Handy keys.** T opens the chat, F6 shows the co-op keys, F10 jumps to the other player (with your car), F3 lets the host restart the mission.
- **Moving between places.** When a mission moves on to a new place, the game waits until both players are at the exit, and your car comes along.
- **Pedestrians, enemies and trams** are fully synced: the same people, the same looks, the same reactions and the same deaths in both games.
- **Police.** Police cars and roadblocks are the same for both players; police on foot are only partly synced, so some foot cops may not look the same in both games. The police react to the second player's crimes and drawn weapons and can arrest either player; the second player sees the handcuff icon and the crime text. Both players can fight and kill cops.

## Current limitations

- **Online sync depends on the connection.** Over the internet, small momentary sync glitches can happen (for example a car or a person jumping a little), depending on the quality of the connection.
- Police on foot are only partly synced.
- Built on the Steam version of *Mafia* (app 40990). It also works on *Mafia* version 1.2. The GOG version has not been tested yet.
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
