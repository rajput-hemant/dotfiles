# Dotfiles

#### My personal dotfiles, for MacOS, managed with [Stow](https://www.gnu.org/software/stow/)

## Usage

- Install [Homebrew](https://brew.sh/)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Install brew bundle

```
brew bundle
```

- Generate a Brewfile

```
brew bundle dump
```

- Clone this repository

```
git clone https://github.com/rajput-hemant/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

- Install dotfiles

```
stow .
```

