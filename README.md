## Hi, I'm George 👋

I build apps and games with Claude and Codex. I decide what gets built, guide the work, and test every result myself before it goes out. Before this I worked in customer success, operations and game audio. I'm based in Athens, Greece.

At the moment I'm working on **games on the Mac**: native ports for Apple silicon, and fixes that help Windows games run well on macOS.

### Native ports

**Time Crisis and Time Crisis II for Mac:** native Apple silicon apps of both arcade games, drawn with Metal, at up to 120 pictures per second, in widescreen, with mouse controls.

- ⬇️ **Free download:** [Time Crisis for Mac 1.0](https://github.com/gkaragioul/namco22-decompile/releases/tag/mac-1.0). It runs on Apple silicon Macs with macOS 13 or newer. Bring your own copy of the arcade game: the app asks for it the first time it opens.
- Offered back to the original decompilation project: [spacestate1/namco22-decompile#99](https://github.com/spacestate1/namco22-decompile/pull/99) *(under review)*

### Open-source contributions

**[Obelisk](https://github.com/Zagrios/Obelisk)**, a Mac launcher that runs Windows games from Steam, Epic and GOG:

- ✅ Steam Cloud saves now sync for games whose rules list the "all" platform, such as Quake: [#36](https://github.com/Zagrios/Obelisk/pull/36) *(merged)*
- ✅ Steam Cloud saves now sync for five games whose rules use different capitalisation: [#43](https://github.com/Zagrios/Obelisk/pull/43) *(merged)*
- Direct3D 12 games that ship the Agility SDK, such as Killing Floor 3, render on the Linux engine: [#67](https://github.com/Zagrios/Obelisk/pull/67) *(under review)*
- A Plague Tale: Innocence renders through DXMT: [#70](https://github.com/Zagrios/Obelisk/pull/70) *(under review)*

**[Voile](https://github.com/Zagrios/Voile)**, Obelisk's Linux engine:

- Windows games can play their videos, through GStreamer: [#2](https://github.com/Zagrios/Voile/pull/2) *(under review)*

**[Homebrew](https://github.com/Homebrew/homebrew-cask)**:

- Obelisk becomes installable with `brew install --cask obelisk`: [#299745](https://github.com/Homebrew/homebrew-cask/pull/299745) *(under review)*

### Bug reports

- Killing Floor 3 stops drawing after about a minute on D3DMetal: [Obelisk#68](https://github.com/Zagrios/Obelisk/issues/68)
- Steam Cloud rules for 12 more games are rejected as unsupported: [Obelisk#42](https://github.com/Zagrios/Obelisk/issues/42)
- The Easy Anti-Cheat bootstrapper crashes at exit in Direct3D 11: [neptune#4](https://github.com/Zagrios/neptune/issues/4)

### Find me

[Website](https://georgekaragioules-ai.vercel.app) · [LinkedIn](https://www.linkedin.com/in/george-karangioules-1207354b/)
