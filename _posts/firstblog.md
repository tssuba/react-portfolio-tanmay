---
date: '2024-01-03T11:50:54.000Z'
title: Extending Minecraft's View Distance
tagline: Truly a game changer
preview: >-
  This will change the way you experience Minecraft and build structures. This
  works both in Singleplayer and Multiplayer, as it is completely client side.
  Server owners can also implement pre-generation server-side, using the server
  side fork available on the discord. It also has shader support on the latest
  version of Iris.
image: >-
  https://wsrv.nl/?url=https%3A%2F%2Fmedia.forgecdn.net%2Fattachments%2F431%2F564%2Fcliff-side-2.png&n=-1
---

# Big Gains with Minimal Performance Loss

**Distant Horizons**, by James Seibel is a Minecraft Mod that works on completely client side ( Single and Multiplayer support ) by using a common but very intelligent solution to rendering terrain that is away from the players POV. It has shader support for Iris shaders, and can be made to work with any shader, and also boast very little performance impact as it is very customizable. Server owners can even implement it to work server-side with configurable performance presets, allowing it to pre-generate terrain for clients, allowing them to view distant terrain prior to exploring the chunk. The server-side fork is available on the discord.

## How it works

The mod uses a common technique called "level of detail", or LODs, that become increasingly simplified as geometry gets further from the player. The mod generates LOD data as the player visits new chunks, or if they enable distant generation which pre-generates that data. Pre-generation can also be enabled on the server-side, and reduces CPU load client-side, and has minimal performance impact if the LODs are already generated, which then only requires bandwidth to transfer that data.

## Links

The mod and links to source code are available at [Modrinth](https://modrinth.com/mod/distanthorizons/gallery).

## 1024 Render Distance

![1024 Render Distance in Minecraft Top Down](https://cdn.modrinth.com/data/uCdwusMi/images/8a194aa0cdd60a695550eb53110a6f61d880db57.jpeg)
