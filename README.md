EKS Chat Commands Script

This script adds immersive and fully customizable roleplay chat commands to your FiveM server — including `/me`, `/do`, `/gme`, `/twitter`, and more. It supports custom usernames, slow mode anti-spam, and a growing list of realistic RP channels.


## Features

Roleplay Emote Commands
- `/me`, `/gme`, `/do` for immersive character actions and scene descriptions  
- `/cctv` and `/trafficam` for in-character camera-based roleplay messages

Themed Chat Channels
- `/twitter` for tweet-style OOC messaging  
- `/darkweb` for anonymous criminal RP messaging

Custom Username System
- `/name <first> <last>` lets players define a custom RP name  
All chat commands will use this name instead of the player’s in-game name.

 Chat Slow Mode
- Prevents spam by enforcing cooldowns per command  
- Cooldown time is fully configurable

Fully Configurable
You can control:
- Cooldown duration per command  
- Local/global visibility  
- Message formatting (prefixes, styles, colors)  
- Which commands are enabled or disabled



## Installation

1. Drag and drop the folder into your `resources/` directory  
2. Add the following to your `server.cfg`:
  Ensure EKS_CC
3 (Optional) Edit `config.lua` to customize cooldowns, formats, and distances.



Notes

- All messages are visible to nearby players unless global  
- Cooldowns are enforced per-player per command  
- Integrates with any framework (ESX, QBCore, standalone)  
- Lightweight and performance-friendly


Support

For help or customization, open a ticket through EKS.

discord.gg/busQ9w6dqa



