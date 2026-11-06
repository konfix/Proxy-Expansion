# Proxy-Expansion for PlaceholderAPI
- This is a PlaceholderAPI expansion, not a plugin. Download the jar from the **Releases** tab and upload it to `plugins/PlaceholderAPI/expansions`
- **Folia-compatible**
- **Velocity and BungeeCord support** (including most of their forks, such as VelocityGD, VeloFlame, Flamecord and others)
- Made for modern Minecraft versions. It might not work on older servers.

## Placeholders

| Placeholder | Example | Description | Example Output |
|-------------|---------|-------------|----------------|
| `%proxy_players_<servername>%` | `%proxy_players_survival%` | Returns the number of online players on the specified server. | `33` |
| `%proxy_players_total%` | `%proxy_players_total%` | Returns the total number of online players across the Velocity or BungeeCord network. | `153` |
| `%proxy_players_here%` | `%proxy_players_here%` | Returns the number of online players on the server the player is currently connected to. | `33` |
| `%proxy_server%` | `%proxy_server%` | Returns the name of the server the player is currently connected to, as defined in the proxy configuration. | `survival` |
| `%proxy_server_caps%` | `%proxy_server_caps%` | Returns the current server name with its first letter capitalized. | `Survival` |

# Credits
- Partly based on and inspired by [PlaceholderAPI's Bungeecord-Expansion](https://github.com/PlaceholderAPI/Bungeecord-Expansion)
