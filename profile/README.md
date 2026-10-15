<img src="https://raw.githubusercontent.com/AshlynSMP/.github/refs/heads/main/assets/ashlynsmp.png">

---
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-swag.svg)](https://forthebadge.com)

The Ashlyn SMP is a private Minecraft survival multiplayer server with unique gameplay mechanics, lore-driven experiences, and custom-built plugins to create an immersive community experience.

## Our Plugins

### [Core](https://github.com/AshlynSMP/Core)
The shared foundation every other Ashlyn SMP plugin builds on:
- **Shared Config** - Server leaders and the lore mode state, available to all plugins through `CoreAPI` / `CoreConfig`
- **Shared Utilities** - Console logger and the text scrambler used for radio interference
- **`/ashlynplugins`** - Lists all Ashlyn SMP plugins installed on the server

### [Radio](https://github.com/AshlynSMP/Radio)
Everything radio on the server:
- **Radio Chat** - During lore mode all chat goes over the radio
- **Radio Towers** - Build a tower with a `[radio]` sign and punch it to take it on- or offline; with one tower down messages get scrambled, with both down the radio goes silent
- **Voice Chat Channels** - Fixed radio frequencies as Simple Voice Chat groups, no custom groups allowed
- **`/broadcast`** (`/bc`) - Server-wide radio announcements for the leaders

### [Credits](https://github.com/AshlynSMP/Credits)
Part of the storyline: plays the Minecraft end credits for one player or the whole server with `/credits`.

### [Propaganda](https://github.com/AshlynSMP/Propaganda)
The original all-in-one server plugin, currently being split up into the plugins above. What's still in here:
- **Ceasefire** - `/wapenstilstand` toggles server-wide PvP
- **Lore Mode** - `/lore` toggles lore mode for the whole server
- **Join, Leave & Death Messages** - Custom messages and the op team prefix
- **World Border Wraparound** - Walk off one edge of the world and come out on the other side

## Resource Packs

### [Season 2 Resource Pack](https://github.com/AshlynSMP/RS-S2)
Custom textures, models, and sounds made specifically for our server's Season 2, enhancing the visual and audio experience of AshlynSMP.

## How It Fits Together

| Plugin | Depends on |
|--------|------------|
| Core | - |
| Radio | Core, [Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat) |
| Credits | Core, [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) |
| Propaganda | - |

## What We Run On

- **Server Software**: Spigot/Paper 1.21+
- **Java Version**: 21
- **[Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat)** - Proximity chat and the radio frequencies
- **[ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/)** - Sending the end credits packet

## Contributing

Want to contribute to the Ashlyn SMP? Check out our individual project repositories for bug reports, feature suggestions, and contribution guidelines.
