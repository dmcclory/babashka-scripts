# setup

1) Make sure that [babashka](https://github.com/babashka/babashka#installation) and [gum](https://github.com/charmbracelet/gum) are installed

on OSX:
```
brew install borkdude/brew/babashka
brew install gum
```

2) clone this repo to a directory (eg `~/.babashka-scripts`)

```
git clone https://github.com/dmcclory/babashka-scripts.git ~/.babashka-scripts/
```

3) in your .zshrc/.bashrc, update your $PATH:

```
export PATH=$PATH:~/.babashka-scripts/bin
```

# usage

these scripts are now available:


- `uuid`: returns a random uuid
- `http-status 202`: given an HTTP status, returns it's description
