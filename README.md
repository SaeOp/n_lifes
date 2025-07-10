## n_lifes

A Minecraft plugin that implements a limited respawn system (9 lives by default)
№Supports Russian and English
## 📦 Installation
Download `n_lifes.jar` from [Releases](https://github.com/yourname/n_lifes/releases)

## 🧾 Commands
| Command                        | Description                       | Permission           |
| ------------------------------ | --------------------------------- | -------------------- |
| `/lifes`                       | Show your current number of lives | `n_lifes.lifescheck` |
| `/n_lifes set <name> <amount>` | Set a player's number of lives    | `n_lifes.admin`      |
| `/n_lifes add <name> <amount>` | Add lives to a player             | `n_lifes.admin`      |

## Configuration
config.yml — main plugin configuration
player_lifes.yml — stores each player's number of lives by their UUID
When a player runs out of lives, they are switched to spectator mode
