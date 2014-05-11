# Neverball

Tilt the  floor to roll a  ball through an obstacle  course within the
given  time.  If  the  ball falls  or time  expires, a ball is lost.

Collect coins to unlock the exit  and earn extra balls.  Red coins are
worth 5.  Blue coins are worth 10.  A ball is awarded for 100 coins.

## Release Notes

Release notes can be found in [doc/release-notes.md](doc/release-notes.md). Below is a summary of highlights.

* Neverball is using Git [on Github][git]!
* Oculus Rift support. This is a compile-time option. Precompiled Windows builds are included in the official download. HMD-enabled builds contain an option to toggle VR mode in the Options screen. Both the Oculus SDK (`make ENABLE_HMD=libovr`) and OpenHMD (`make ENABLE_HMD=openhmd`) backends are supported.
* An OpenGL ES-compatible renderer. All of the Neverball rendering code has been rewritten for OpenGL ES 1.1 compliance to ease porting efforts to mobile/embedded platforms.
* Port to SDL 2. Amongst other things, this fixes a number of fullscreen-related issues and vastly improves multiple display support.
* [Mapping documentation][mapping]!

## Documentation

* [LICENSE.md](LICENSE.md): a description of licensing and exceptions
* [doc/install.txt](doc/install.txt): instructions on how to build the
  game from source code
* [doc/manual.txt](doc/manual.txt): a detailed description of how to
  play and configure the game
* [doc/authors.txt](doc/authors.txt): a list of people who have
  contributed to Neverball

## Resources

* [Website](http://neverball.org/)
* [Development](http://github.com/Neverball)
* [Neverforum](http://forum.nevercorner.net/)
* [Nevertable](http://table.nevercorner.net/) (high-score and replay
  database)
* [#neverball on chat.freenode.net](http://webchat.freenode.net/)

## Translation

Neverball uses the gettext approach to translations. We're always
interested in covering more languages. We have a project on Transifex
(see [instructions on the forum][tx]) and we also accept PO files.

[tx]: http://forum.nevercorner.net/viewtopic.php?id=2741