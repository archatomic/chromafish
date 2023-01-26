# Chromafish's Guide to Minecraft Servers
I have two [on-demand](#what-does-on-demand-mean) Minecraft servers ready to play on if you're a member of my discord. This guide should get you connected to either and get you started with modding, if (like me) you've never done it before.

## Table of Contents
1. [Java Edition Multiplayer Server (Bushwa)](#bushwa)
    - [Connecting](#connecting-to-bushwa---modded)
    - [Using vanilla minecraft](#connecting-to-bushwa---vanilla)
1. [Bedrock Edition Multiplayer Server (Zounds)](#zounds)
    - [Connecting](#connecting-to-zounds)
1. [Frequently Asked Questions](#faq)
    - [What does an "on-demand" server mean?](#what-does-on-demand-mean)
    - [What mods can I install?](#what-other-mods-can-i-install)
    - [How do I make Minecraft better than real life?](#how-do-i-make-minecraft-really-pretty)
    - [My laptop is actually a toaster that I duct-taped to a cat. How should I run my Minecraft streams?](#how-do-i-make-minecraft-really-fast)
    - [What mods are you running, Chromafish?](#what-mods-are-you-running-chromafish)

## Bushwa
A casual Java survival server for PC players who want to mod their clients, or PC players who don't want to / can't use Bedrock Edition.

If you want proxy voice chat, this is also the server you should connect to.

### Server Details
- Minecraft Java Edition required
- Version - 1.19.2
- Forge server
- [Cold Boot Time - 5 minutes](#what-does-on-demand-mean)
- 2 CPUs, 8gb RAM

#### Serverside Mods
- [Ferrite Core](https://modrinth.com/mod/ferrite-core) - Optimization
- [Starlight](https://modrinth.com/mod/starlight-forge) - Optimization
- [Simple Voice Chat](https://modrinth.com/mod/simple-voice-chat) - Proximity voice

### Connecting to Bushwa - Modded
This is the recommended way to connect to Bushwa, and will enable you to use the in-game proxy voice chat and easily modify your Minecraft install.

1. Download the [Prism Launcher](https://prismlauncher.org/)
1. Make sure you have [Java 17 installed and configured](https://prismlauncher.org/wiki/getting-started/installing-java/)
1. [Click Add Instance](https://prismlauncher.org/wiki/getting-started/create-instance/) and set it to version 1.19.2.
1. In the bottom right "Mod Loader" list, select "Forge" and click "OK"
    - You should see your new instance show up in your window
1. Install the ["Simple Voice Chat" mod from Modrinth](https://prismlauncher.org/wiki/getting-started/download-mods/)
    - This mod is the **only required mod** to access Bushwa this way, but [you can still install other client-side mods if you like.](#what-other-mods-can-i-install)
1. Launch your new instance and navigate to "Multiplayer"
1. Click "Add Server" and set the server address to "bushwa.chromafish.com"
1. Click "Done"

You are now free to connect to the server. [If the server times out when you attempt to connect, wait 5 minutes and try again.](#what-does-on-demand-mean)

### Connecting to Bushwa - Vanilla
If you prefer to not run any mods or 3rd party software, you can connect to the server with just the Mojang (vanilla) launcher. The only thing you will miss out on is the ability to use the proximity voice chat feature, and to modify your experience. Eventually there may be more content you can't access, but I will continue to try and support the vanilla launcher moving forward.

1. Download the [Minecraft Launcher](https://www.minecraft.net/en-us/download) if you don't already have it.
1. Open the launcher and [change your version to 'release 1.19.2'](https://help.minecraft.net/hc/en-us/articles/360034754852-Change-Game-Version-for-Minecraft-Java-Edition#:~:text=Click%20Installations%20on%20the%20launcher,Play%20on%20the%20top%20menu.)
1. Launch Minecraft and navigate to "Multiplayer"
1. Click "Add Server" and set the server address to "bushwa.chromafish.com"
1. Click "Done"

You are now free to connect to the server. [If the server times out when you attempt to connect, wait 5 minutes and try again.](#what-does-on-demand-mean)

## Zounds
A casual Bedrock survival server, meant for those of us on consoles, mobile devices, or who prefer a more controlled experience.

### Server Details
- Minecraft Bedrock Edition required
- Crossplay supported (Windows / Console / Mobile, etc.)
- [Cold Boot Time - 2 minutes](#what-does-on-demand-mean)
- 2 CPUs, 8gb RAM

#### Serverside Add Ons
None so far

### Connecting to Zounds
1. Launch Minecraft and navigate to "Multiplayer"
1. Click "Add Server" and set the server address to "zounds.chromafish.com"
1. Click "Done"

You are now free to connect to the server. [If the server times out when you attempt to connect, wait 2 minutes and try again.](#what-does-on-demand-mean)

## FAQ
### What does "On Demand" mean?
To save on cost, I am not running these servers 24/7. If the server sits with nobody connected to it (for about 20 minutes), it shuts down automatically.

The first time you tries to connect while the server is offline, you will get some kind of a "connection timed out" error. This is normal, and the server will now automatically come back online. The total time this takes is the **cold boot time**.

Once a couple of minutes have passed, try again and you should be able to connect just fine!

### What other mods can I install?
**Java Edition Only** The answer here is "Try and see," but I've put together a couple of recommendations below, if you want [a really pretty experience](#how-do-i-make-minecraft-really-pretty), or if you are [trying to run Minecraft on a potato](#how-do-i-make-minecraft-really-fast). I've also provided a [list of mods I am currently running](#what-mods-are-you-running-chromafish).

### How do I make Minecraft really pretty?
**Java Edition Only** You need shaders, and a mod to run them. I recommend using [Optifine](http://optifine.net/adloadx?f=OptiFine_1.19.2_HD_U_I1.jar). Once you've downloaded the file, open Prism, open the edit panel for your 1.19.2 instance, and drag the jar file you just downloaded into the mod list.

[You can now add shaders to the "Shader Pack" list.](#shaders)

### How do I make Minecraft really fast?
**Java Edition Only** Let's talk optimizations. I would focus on mods that make your client run better. You might have better luck trying a bunch of different mods and seeing. [Here's a filtered list of forge client optimization mods](https://modrinth.com/modpacks?f=categories%3A%27optimization%27&g=categories%3A%27forge%27&e=client). I'm running these optimization mods on my client:

1. Ferrite Core
1. EntityCulling
1. Ksyxis
1. Optifine
    - You can use Optifine to run really intense shaders, sure, but it also can be used to run super simple ones. It also comes bundled with a ton of options that should help speed your potato up.

### What mods are you running, Chromafish?
**Java Edition Only** Oh gee, thanks for asking. As of writing this guide, here is the complete list of what I've got installed.

#### MODS
Most of these are installable through the mods / download mods interface in Prism.
1. **Simple Voice Chat**
    - Modrinth
    - REQUIRED - adds proximity chat support to Bushwa.
1. Ambient Sounds
    - Modrinth
    - The jury is still out on this one, but it's supposed to add a bunch of outdoorsy sounds to your game. I haven't actually noticed any difference yet.
1. Better F3
    - Modrinth
    - Fixes the "Wall of text" default F3 by letting you customize and color code all of that information.
1. Cloth Config API
    - Modrinth
    - Adds some mod config menus, so I can edit settings in game.
1. Controllable
    - CurseForge
    - Adds some controller support to Java Edition
1. EntityCulling
    - Modrinth
    - Optimization that boosts performance by keeping minecraft from trying to render blocks that are behind other blocks (and therefore invisible)
1. Ferrite Core
    - Modrinth
    - Memory usage optimizations. I use this on the server too.
1. Just Enough Items (JEI)
    - CurseForge
    - Adds a little item recipe wiki into the game's crafting windows. Just a quality of life thing.
1. Ksyxis
    - Modrinth
    - Optimizes Minecraft load times by not loading a huge number of chunks when you load a world.
1. OKZoomer
    - Modrinth
    - A little "push hotkey to zoom" utility. It's not perfect, but it is the only one I found that didn't require a second mod to work.
1. [Optifine](#how-do-i-make-minecraft-really-pretty)
    - Manual install required
    - Allow the use of shaders and give me a bunch of clientside optimizations
1. Sound Physics Remastered
    - Modrinth
    - Adds area reverb to sound effects in the game and to voice chat. It's actually really cool with headphones on.

#### RESOURCE PACKS
I'm a Minecraft Baby, but from what I can tell [Modrinth](https://modrinth.com/resourcepacks) and [CurseForge](https://www.curseforge.com/minecraft/texture-packs) are both pretty good places to find all sorts of resources.

My favorite so far is [Faithless](https://www.curseforge.com/minecraft/texture-packs/faithless) which does a lot to enhance the interface and icons with better pixel art.

I am also looking for some good PBR textures, so if anyone has ideas, please let me know in the Discord.

#### SHADERS
[Modrinth](https://modrinth.com/shaders) is still a pretty good resource here, though CurseForge doesn't seem to have shaders as much.

The two I go back and forth between are:
1. [BSL Shader](https://modrinth.com/shader/bsl-shaders), which gives you a realistic look and lets you support some advanced (PBR) texture packs
1. [Sildur's Vibrant Shaders](https://sildurs-shaders.github.io/downloads/) which has some really pretty volumetric lighting and has more saturated, colorful experiences.

## Other questions?
[Join the Discord](https://discord.gg/jCY2x4MW) and ask there.
[Follow me on Twitch](https://twitch.tv/thechromafish) for game streams, and to get updates on my WIP indie game, The Collector.
