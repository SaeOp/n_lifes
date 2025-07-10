## n_lifes

A Minecraft plugin that implements a limited respawn system (9 lives by default)
Supports Russian and English
## 📦 Installation
Download `n_lives.jar` from [Releases](https://github.com/yourname/n_lifes/releases)

## 🧾 Commands
| Command                        | Description                       | Permission           |
| ------------------------------ | --------------------------------- | -------------------- |
| `/lives`                       | Show your current number of lives | `n_lifes.livescheck` |
| `/n_lives set <name> <amount>` | Set a player's number of lives    | `n_lifes.admin`      |
| `/n_lives add <name> <amount>` | Add lives to a player             | `n_lifes.admin`      |

## Configuration
config.yml — main plugin configuration
player_lives.yml — stores each player's number of lives by their UUID
When a player runs out of lives, they are switched to spectator mode

# Placeholders (requires papi)
%nlives_lives% - return player lives
