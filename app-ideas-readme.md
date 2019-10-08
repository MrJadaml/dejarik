# Table Top Board Game OS

A "distro" for playing and building hybrid digital table top board games.

## Features

Should be designed around a table top display.
Should have an app store
Should have an SDK for creating apps
Should provide non-developer tools/interface for designing games
- Default apps ex. iOS -> Camera, Photos, App Store, Game Center
Should have universal messaging/user-aaccount system
- This could be integrated into games
- Could create "universial" avatars/characters that could be used across differnt games.
  - Inest more into an avatar/character persona that is portable than haveing to create one for each game
  - Games could extend these avatars for game specifc mechanics/traits
  - Users could have a "cast" of avatars/characters
  - Multiple players can sign into the table-top to pull up their "cast" of characters
    - Phone sync -- kinda like how you sign on to YouTube on Roku??
Should have touch interaction option, but should be able to work without.


### Notes

Look through [Board Game Geek] to get an idea for commmon patterns of designs, pieces, cards, layouts, mechanics etc.

A company called [PlayTable] has something very similar to what I am thinking. Though theirs it tied to proprietary hardware. I think a more insteresting approach
would be for this to be hardware agnostic. Anyone who downloads the OS can put it on whatever hardware they have, Create DIY tables, etc. Inline with this:
- https://www.enworld.org/threads/digital-gaming-tables.477324/post-7064173
- https://www.enworld.org/threads/digital-gaming-tables.477324/post-7060716

The cost to develop a more portable system would likely be far less than developing and manufacturing proprietary hardware. Just let folks by displays off Amazon.
Provide some basic instructions for setting up with a common/inexpensive display and arduino/mini-pc. I would imagine with the pervasive use of 3D printers, the type
of people who would be early adopters for this would also have shared lots of 3D printed stands. Also could create a partnership with someone like [Wyrmwood] to create
nice attractive tables.

Potential monitization of this I don't think would be though propritary hardware. I think actually that would actually just create a barrier for adoption/use
and reduce the player pool. I think the OS would also be free to encourage further adoption, also potentially OSS? I think the real monitizatioin of this
is though an "App Store" at scale (hense no propritary hardware and free OS download)

Mabye an option to be compatible with Steam??

[Touch screen object interaction]

[Yucata] does game mechanics/status tracking well. They would be an interesting resouce to look into for getting ideas on that end of things.

### Tech

[Arch], [Manjaro], [Debian] ??
[Rust]
[WebAssembly], [Wasmer]
- https://medium.com/wasmer/running-webassembly-on-the-kernel-8e04761f1d8e

### Resources 📚

[Board Game Geek]: https://www.boardgamegeek.com/browse/boardgame?sort=bggrating&sortdir=desc
[Tabletopia]: https://tabletopia.com/about
[Board Game Arena]: https://en.boardgamearena.com
[Yucata]: https://yucata.de/en
[PlayTable]: https://www.playtable.com/
[Wyrmwood]: https://wyrmwoodgaming.com/furniture/
[Touch screen object interaction]: https://www.instructables.com/id/Object-Interaction-With-Touchscreens/
[WebAssembly]: https://webassembly.org
[Wasmer]: https://wasmer.io/
