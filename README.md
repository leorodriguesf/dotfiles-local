[anishathalye/dotfiles-local]:
  https://github.com/anishathalye/dotfiles-local/tree/master
[anishathalye/dotbot]: https://github.com/anishathalye/dotbot
[dotfiles]: https://github.com/leorodriguesf/dotfiles
[LICENSE]: LICENSE

# Dotfiles (local)

> Inspired by [anishathalye/dotfiles-local] and powered by [anishathalye/dotbot]

After cloning this repo, make sure you are **on the right machine-specific
branch**, then run `install` to automatically set up the development
environment. Note that the install script is idempotent: it can safely be run
multiple times.

This repository contains machine-specific configuration to accompany my
[dotfiles][dotfiles]. The actual contents of this repository probably will not
be useful to anyone but me, but others may be interested in seeing how these
files are organized.

## Branch Hierarchy

```
.
├── macos
├── macos-work
├── ubuntu
├── ubuntu-work
└── ...
```

Configuration for specific computers (or groups of computers) is maintained in
separate branches in this repo.

## License

Released under the MIT License. See [LICENSE] for details.
