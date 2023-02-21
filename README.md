# An awesome-style list of osu! projects. [![Support Server](https://img.shields.io/discord/211953616918020107.svg?color=7289da&label=Circle%20People&logo=discord&style=flat-square)](https://discord.gg/circlepeople)

## Table of contents

![wip](https://img.shields.io/badge/note-Work%20in%20progress-yellow)

## Official osu! projects

| URL                                                   | Description/Notes                                                                                    |
| ----------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| [osu!](https://osu.ppy.sh)                            | The official website for the rhythm game osu!.                                                       |
| [osu!lazer](https://github.com/ppy/osu)               | osu!lazer source code, the next generation client for osu!                                           |
| [osu!web](https://github.com/ppy/osu-web)             | osu!'s website source code                                                                           |
| [osu!wiki](https://github.com/ppy/osu-wiki)           | The home of the community-managed wiki for osu!                                                      |
| [osu!framework](https://github.com/ppy/osu-framework) | The framework that powers osu!, including features that can be used to make other games/applications |
| [other osu! projects](https://github.com/ppy)         | Other official osu!team projects can be found here.                                                  |

## Gameplay

### Alternative game clients

These are game clients that *do not connect to osu! servers*, but may be useful for practice, writing tools or other things.

| Client                                                    | Description                                              |
| --------------------------------------------------------- | -------------------------------------------------------- |
| [opsu!](https://itdelatrisu.github.io/opsu/)              | Unofficial osu! client in Java                           |
| [osu!droid](http://ops.dgsrz.com/)                        | An open-source client for osu! on the Android platform   |
| [McOsu](https://store.steampowered.com/app/607260/McOsu/) | An osu! client designed for practice, with VR support    |
| [Danser][4]                                               | open-source osu! visualisation and replay recording tool |

### Rulesets

| URL                                                                      | Description/Notes                            |
| ------------------------------------------------------------------------ | -------------------------------------------- |
| [Custom ruleset directory](https://github.com/ppy/osu/discussions/13096) | Official directory for lazer custom rulesets |

### Beatmap mirrors

| Mirror                                 | Description/Notes                             |
| -------------------------------------- | --------------------------------------------- |
| [Beatconnect](https://beatconnect.io/) | Comprehensive beatmap mirror with API support |
| [Nerinyan](https://nerinyan.moe/)      |                                               |
| [Kitsu](https://kitsu.moe/)            |                                               |
| [Chimu](https://chimu.moe/)            |                                               |
| [Mino](https://catboy.best/)           |                                               |

### Skins

![wip](https://img.shields.io/badge/note-Work%20in%20progress-yellow)

| URL                                                  | Description/Notes                            |
| ---------------------------------------------------- | -------------------------------------------- |
| [rudj skinhub](https://github.com/rudj-skinhub/woal) | Collection of skin sources from many players |

### Chatbots (Discord)

| Bot                                                   | Description/Notes                                                   |
| ----------------------------------------------------- | ------------------------------------------------------------------- |
| [owo!](http://owo-bot.xyz/)                           | Popular osu! tracking and score bot                                 |
| [Sunny][3]                                            | osu! bot with support for restricted users and osu! login           |
| [Bathbot][1]                                          | Feature-rich bot for osu!                                           |
| [Quna][2]                                             | Actively developed osu! bot that supports unranked score submission |
| [MissAnalyzer](https://top.gg/bot/752035690237394944) | osu! bot for replay analysis                                        |
| [Yuna](https://top.gg/bot/832597585923014676)         | osu! replay recording bot                                           |
| [Shisha](https://shisha.mezo.xyz/)                    | osu! replay recording bot approved by the creator of [danser][4]    |
| [Sombrax79](https://ost.sombrax79.org/commands)       | Bot for stamina training recoomendations                            |

### Bots (in-game)

| Bot                                                         | Description/Notes                        |
| ----------------------------------------------------------- | ---------------------------------------- |
| [Tillerino](https://github.com/Tillerino/Tillerinobot/wiki) | Bot for beatmap recommendations          |
| [Sombrax79](https://ost.sombrax79.org/commands)             | Bot for stamina training recoomendations |

### Streaming tools

| Tool                                                             | Description                                                          |
| ---------------------------------------------------------------- | -------------------------------------------------------------------- |
| [StreamCompanion](https://github.com/Piotrekol/StreamCompanion/) | A tool for streamers featuring a PP counter, map overlays, and more! |
| [Ronnia](https://ronnia.me/)                                     | Twitch bot for linking maps from Twitch to ingame chat               |

### Chat clients

![wip](https://img.shields.io/badge/note-Work%20in%20progress-yellow)

## Mapping

![wip](https://img.shields.io/badge/note-Work%20in%20progress-yellow)

## Development

### API libraries

| Library                                                           | Language   | Description/Notes                                             |
| ----------------------------------------------------------------- | ---------- | ------------------------------------------------------------- |
| [aiosu](https://github.com/niceaesth/aiosu)                       | python     | Async python library for interacting with the osu! API.       |
| [ossapi](https://github.com/circleguard/ossapi)                   | python     | Synchronous python library for interacting with the osu! API. |
| [osu-api-extended](https://github.com/cyperdark/osu-api-extended) | typescript |                                                               |
| [rosu-v2](https://github.com/MaxOhn/rosu-v2)                      | rust       | Actively maintained osu!apiv2 wrapper                         |
| [rosu](https://github.com/MaxOhn/rosu)                            | rust       |                                                               |

### Utility libraries

| Library                                                           | Language   | Description/Notes                                                                        |
| ----------------------------------------------------------------- | ---------- | ---------------------------------------------------------------------------------------- |
| [rosu-pp](https://github.com/MaxOhn/rosu-pp)                      | rust       | Standalone crate to calculate star ratings and performance points for all osu! gamemodes |
| [osu-classes](https://github.com/kionell/osu-classes)             | typescript | Rewrite of the basic class structure of osu!lazer in TypeScript                          |
| [osu-parsers](https://github.com/kionell/osu-parsers)             | typescript | A bundle of TS parsers for all osu! data formats                                         |
| [osu-pp-calculator](https://github.com/kionell/osu-pp-calculator) | typescript | The most up-to-date TS star rating/performance calculator library                        |
| [gosu-pp](https://github.com/Wieku/gosu-pp)                       | go         | Port of osu!lazer difficulty and performance calculator in go                            |
| [rosu-pp-py](https://github.com/MaxOhn/rosu-pp-py)                | python     | Python bindings for rosu-pp                                                              |
| [rosu-pp-js](https://github.com/MaxOhn/rosu-pp-js)                | javascript | JS bindings for rosu-pp                                                                  |
| [akatsuki-pp-go](https://github.com/osuAkatsuki/akatsuki-pp-go)   | golang     | Go bindings for rosu-pp                                                                  |
| [akatsuki-pp](https://github.com/osuAkatsuki/Akatsuki.PP)         | c#         | c# bindings for rosu-pp                                                                  |
| [bancho.js](https://github.com/ThePooN/bancho.js)                 | javascript | ThePoon's bancho library                                                                 |
| [slider](https://github.com/llllllllll/slider)                    | python     | osu! file format parser                                                                  |

## Other projects

| URL                                                                                  | Description/Notes                                             |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------- |
| [osu! matchmaking](https://oma.hwc.hr/)                                              | Competitive matchmaking system for osu!                       |
| [minipad](https://github.com/minipadkb)                                              | Open-Source wooting-like analog keypad with rapid trigger     |
| [osu! batch beatmap downloader](https://github.com/nzbasic/batch-beatmap-downloader) | Tool for easily downloading large amounts of osu! maps        |
| [osu-trainer](https://github.com/FunOrange/osu-trainer)                              | Tool, that allows you to create speed up difficulties of maps |
| [OpenTabletDriver](https://github.com/OpenTabletDriver/OpenTabletDriver)             | Open source, cross-platform, user-mode tablet driver          |

---

## Contributing

Feel free to join the Discord above and join the thread for this list if you want to improve it!
Alternatively, create a discussion if you want to discuss here on GitHub.

This document is a work in progress. Feel free to add your project here by forking the repository and adding your project via a Pull Request.

Please follow these guidelines when adding a project:

- Familiarize yourself with [Markdown](https://www.markdownguide.org/cheat-sheet/) so you don't break things.
- Provide some (concise) details about your project.
- Avoid using link shorteners when possible.
  - These are hard to moderate and deal with, hard links are appreciated (ex. A clean Discord invite link, a website, or a Git page for your bot)
  - Long links can be dealt with by using [reference style links](https://www.markdownguide.org/basic-syntax/). This helps people using the web editor to help readability.
  - If you link to another project in the description that is already on this page, use a reference style link as well.
- This goes without saying, but it should be relevant to osu!.
  - It also should not break osu! rules (ex. tools that give advantages that interact with the client, custom servers, etc.) If you don't know, ask.

## Notice

This document is released under the CC BY-SA 4.0 license. **Circle People is not affiliated with & does not endorse any projects listed above.**
"osu!" and "ppy" are trademarks of ppy Pty Ltd. & are not affiliated with Circle People.

[//]: <> (Reference links.)

[1]: https://discord.com/api/oauth2/authorize?client_id=297073686916366336&permissions=309238025216&scope=bot%20applications.commands
[2]: https://discord.com/api/oauth2/authorize?client_id=957969843343200276&permissions=2147863616&scope=applications.commands%20bot
[3]: https://discord.com/oauth2/authorize?client_id=376679719044907019&scope=bot
[4]: https://github.com/Wieku/danser-go