> :warning: In development. There is not currently a full release.

# Sol Client


<a href="https://github.com/TheKodeToad/Sol-Client/actions/workflows/build.yml"><img src="https://img.shields.io/github/workflow/status/TheKodeToad/Sol-Client/build?style=for-the-badge&logo=github&logoColor=white"/></a>&nbsp;
<img src="https://img.shields.io/static/v1?label=you%20didn%27t&message=ask%20for%20this&color=blue&style=for-the-badge"/>&nbsp;
<img src="https://img.shields.io/static/v1?label=minecraft&message=1.8.9&color=brightgreen&style=for-the-badge"/>&nbsp;
<a href="https://discord.gg/QFDGDhcFqu"><img src="https://img.shields.io/discord/886561982872977408?color=5662F6&label=discord&logo=discord&logoColor=white&style=for-the-badge"/></a>

Simple and lightweight Minecraft client for 1.8.9 (and in future, newer versions).

## Gimme it now!
First, go to [releases](https://github.com/TheKodeToad/Sol-Client/releases).

Next, download the latest version for your OS. If there is a security warning, this is because we haven't spent any money on software signing.

## Why?
There are many Minecraft clients, but they are usually closed source, and may contain malicious code.

There may be mod loaders like Forge and Fabric, which are perfectly good, but are not as simple and easy to use.

## Safety
I open sourced this client because not enough clients are open source (even OptiFine is closed source).

If you are suspicous, you can easily look through all the code.

This client has been tested by multiple people on Hypixel, and it disables disallowed mods automatically.

## Credits
[TheKodeToad](https://github.com/TheKodeToad) / [mcblueparrot](https://mine.ly/mcblueparrot.1): Programmer.

[Holso](https://github.com/Holso) / [GreenDracon](https://mine.ly/IceDracon.1): Helped create Discord, came up with the name and tested the client.

[sp614x](https://github.com/sp614x): OptiFine mod.

[Sk1er LLC](https://github.com/Sk1erLLC): Mod inspiration.

[Hyperium](https://github.com/HyperiumClient/Hyperium): Some rendering and launching code.

[Eric Golde](https://www.youtube.com/c/egold555): My older private client followed his tutorials.

[tr7zw](https://github.com/tr7zw/EntityCulling): Original EntityCulling mod. A ported version is used in this client.

[OrangeMarshall](https://namemc.com/profile/OrangeMarshall.1): Original 1.7 Animations.

## Features
- Most features from Lunar.
- Hypixel Additions (pop-up events, better channel switcher (shows channel name in chat box).
- Better item tooltips (shows item damage).
- Symbol picker (and maybe Emoji support?).
- OptiFine, downloaded automatically from the official site.

Click [this fancy blue text](https://github.com/TheKodeToad/SolClient/projects/1) to see planned features.

## Build Instructions

### Launcher

Setup:
```sh
npm i
```

Start Launcher:
```sh
npm run start
```

Build Executable:
```sh
npm run make
```

### Game

Move into folder:
```sh
cd game
```

Setup:
```sh
./gradlew setupDecompWorkspace
```

Build JAR:
```sh
./gradlew build
```

