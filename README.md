# Homebrew tap

Install [drivethru](https://github.com/ja-godfrey/drivethru), a local Google
Drive file picker that copies share links and opens the right browser account:

```sh
brew install ja-godfrey/tap/drivethru
drivethru doctor
drivethru
```

Requires macOS 13 or later and Google Drive for desktop. Homebrew installs fzf.
See the [project README](https://github.com/ja-godfrey/drivethru#readme) for
configuration, hotkeys, and the optional Finder Quick Action.

To upgrade:

```sh
brew update
brew upgrade ja-godfrey/tap/drivethru
```
