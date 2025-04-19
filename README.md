# Primosputt
### My personal Neverball fork that adds 5-player support and other quality-of-life features to Neverputt.

![Neverball](https://neverball.org/images/shots/01-neverball-easy/easy-07-01.jpg)

##### (TODO: change this image to a screenshot of the titlescreen)

It was made in about a day mostly just to play with my cousins, so expect bugs and other issues.
(I didn't change a lot tho, just about ~130 lines, and that's counting with all the color changes and renaming, so it should be fairly stable)

If you just want the code for TAB key function to force a penalty check out the `tab` branch. It's based on [this pull request](https://github.com/Neverball/neverball/pull/99).

Want to play it? Uhh, then go to [doc/install.txt](doc/install.txt) compile it yourself idk. I'm probably not going to make a release anytime soon. Tip: If you want to compile for Windows, it's best to use the docker container in [doc/alpha.md](doc/alpha.md). (I tried cross-compiling for windows and it just gave me headaches.)

## New features

- You can now use `TAB` to force a penalty (useful if your ball gets stuck in a moving platform)
- Support for 5 players, of course (if you for some reason need more it should be fairly easy to change)
- Not really a new feature, but I changed the player and ball colors to my cousins' favourite ones :)
- Uhh rebranding for some reason, was in the mood for it

## Planned features

- Add a button to skip a hole in the pause menu, based on [this pull request](https://github.com/Neverball/neverball/pull/326)

---
# Regular Neverball stuff

## Release Notes

Release highlights can be found in [doc/release-notes.md](doc/release-notes.md).

## Documentation

* [LICENSE.md](LICENSE.md): a description of licensing and exceptions
* [doc/install.txt](doc/install.txt): instructions on how to build the
  game from source code
* [doc/manual.txt](doc/manual.txt): a detailed description of how to
  play and configure the game
* [doc/authors.txt](doc/authors.txt): a list of people who have
  contributed to Neverball

## Resources

* [Website](https://neverball.org/)
* [Development](http://github.com/Neverball)
* [Discord](https://discord.gg/HhMfr4N6H6)

## Translation

Neverball uses the gettext approach to translations. We're always
interested in covering more languages. Join the
[Neverball project on Transifex](https://www.transifex.com/neverball/neverball/).
