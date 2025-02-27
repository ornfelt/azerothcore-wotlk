# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore

## My custom changes

My custom changes include:
* Arena skirmish with npcbots. Currently, I've only added Nagrand Arena. You can queue 2v2, 3v3 and 5v5 and the npcbots will automatically join the queue just like in BGs. You need [this](https://github.com/ornfelt/azerothcore-wotlk/commit/f7856d31eb32975d43cc8b849526e46c85594b8c) commit and the Nagrand arena wander nodes (my sql can be found [here](https://github.com/ornfelt/azerothcore-wotlk/blob/master/data/sql/custom/db_world/2023_06_09_00_creature_template_npcbot_wander_nodes.sql)) to add arena, and ideally [this](https://github.com/ornfelt/azerothcore-wotlk/commit/0739541191eff3c91ee91e1eb31673cecb84bb88) one as well.

* Compatability with https://github.com/ornfelt/wander_nodes_util. See [this](https://github.com/ornfelt/azerothcore-wotlk/commit/2399ea767097d2a227aa37c860c1feee63e27598#diff-821d8443e5562c441172343cb58672bed4f1275e800e3ea08e9436c5eb2f4e7a) commit for required changes (look for DB execution in bot_ai.cpp and botdatamgr.cpp).

## Build Status

3.3.5
:------------:
[![Clang](https://github.com/trickerer/AzerothCore-wotlk-with-NPCBots/actions/workflows/core_build.yml/badge.svg)](https://github.com/trickerer/AzerothCore-wotlk-with-NPCBots/actions/workflows/core_build.yml)
[![Build status](https://ci.appveyor.com/api/projects/status/9cd8gd9io83l3v14/branch/npcbots_3.3.5?svg=true)](https://ci.appveyor.com/project/trickerer/azerothcore-npcbots/branch/npcbots_3.3.5)

## Introduction

AzerothCore is an open-source game server application and framework designed for hosting massively multiplayer online role-playing games (MMORPGs). It is based on the popular MMORPG World of Warcraft (WoW) and seeks to recreate the gameplay experience of the original game from patch 3.3.5a.
The original code is based on MaNGOS, TrinityCore, and SunwellCore and has since then had extensive development to improve stability, in-game mechanics, and modularity to the game. AC has also grown into a community-driven project with a significant number of contributors and developers. It is written in C++ and provides a solid foundation for creating private servers that mimic the mechanics and behavior of the official WoW servers.

[NPCBots](https://github.com/trickerer/Trinity-Bots) is AzerothCore mod.


## Installation

Installation instructions are available [here](http://www.azerothcore.org/wiki/Installation).

NPCBots installation guide is available in the [NPCBots Readme](https://github.com/trickerer/Trinity-Bots#npcbot-mod-installation).


## Support

AzerothCore self-made wiki probably has a lot of answers for you.

For help requests, it is recommended to ask your question on [StackOverflow](https://stackoverflow.com/questions/tagged/azerothcore) and link it in [our chat](https://discordapp.com/channels/217589275766685707/284406375495368704).


## Reporting issues

NPCBots issues can be reported via the [Github issue tracker](https://github.com/trickerer/Trinity-Bots/issues/).

Please take the time to review existing issues before submitting your own to
prevent duplicates.


## Submitting fixes

C++ fixes are submitted as [pull requests](https://github.com/trickerer/Azerothcore-wotlk-with-NPCBots/pulls).


## Important Links

- [NPCBots Readme](https://github.com/trickerer/Trinity-Bots/)

- [Website](http://www.azerothcore.org/)
- [AzerothCore catalogue](http://www.azerothcore.org/catalogue.html  "Modules, tools, and other stuff for AzerothCore") (modules, tools, etc...)
- [AzerothCore Discord server](https://discord.gg/gkt4y2x)
- [AzerothCore wiki](http://www.azerothcore.org/wiki "Easy to use and developed by AzerothCore founder")
- [AzerothCore forum](https://github.com/azerothcore/azerothcore-wotlk/discussions/)
- [AzerothCore Facebook page](https://www.facebook.com/AzerothCore/)
- [AzerothCore LinkedIn page](https://www.linkedin.com/company/azerothcore/)


## License

- The new AzerothCore source components are released under the [GNU AGPL v3](https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE-AGPL3)
- The old sources based on MaNGOS/TrinityCore are released under the [GNU GPL v2](https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE-GPL2)


It's important to note that AzerothCore is not an official Blizzard Entertainment product, and it is not affiliated with or endorsed by World of Warcraft or Blizzard Entertainment. AzerothCore does not in any case sponsor nor support illegal public servers. If you use this project to run an illegal public server and not for testing and learning it is your own personal choice.
