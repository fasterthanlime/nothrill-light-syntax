# nothrill-light-syntax theme

An atom fork of the [nofrils theme][] for vim. Originally created by Robert Melton.

![Nothrill for atom screenshot](https://github.com/fasterthanlime/nothrill-light-syntax/blob/master/nothrill-light-screenshot.png?raw=true)

(This fork is itself a fork of JonathanMH's [nothrill-dark-syntax][])

Differences from Robert Melton's nofrils theme:

  * Comments are emphasized (they're darker on a clear background) rather than
  de-emphasized.
  * Selection is light-gray rather than the original's black, because there's currently no way
  to [change selected text color in Atom](https://github.com/atom/atom/issues/2886)

Other notes:

  * When searching via vim-mode (with `/`), results aren't highlighted - that's
 because vim-mode doesn't apply any special class to them, so they can't be styled.

[nofrils theme]: https://github.com/robertmeta/nofrils
[nothrill-dark-syntax]: https://github.com/jonathanmh/nothrill-dark-syntax
