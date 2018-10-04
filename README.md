# Keep Your macOs Stuff Updated (KYMSU)

> Get your Homebrew, Mac App Store, Atom Package Manager (apm), NPM, Yarn, Composer ... stuff updated.

## Requirements

- [Homebrew](https://brew.sh)
- [mas](https://github.com/mas-cli/mas)

## Installation

`$ git clone git@github.com:welcoMattic/kymsu.git && cd kymsu && ./install.sh`

## Usage

```shell
# Only update all the things
$ kymsu

# With cleanup after updates
$ kymsu cleanup
```

## Plugins system

All default plugins are placed in `~/.kymsu/plugins.d`, feel free to delete those you don't use, and/or add new ones.
Don't forget to share them here with a shiny pull request! ✨

## Auto-update

KYMSU will auto-update itself each time you run `kymsu` command.