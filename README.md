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

## Mouse Gestures

This repository includes a comprehensive mouse gestures setup for macOS using xGestures. The setup provides intuitive mouse gestures for window management and desktop navigation.

📁 **Location**: [`mouse-gestures/`](./mouse-gestures/)

🔗 **Full Documentation**: See [`mouse-gestures/README.md`](./mouse-gestures/README.md) for complete setup instructions, gesture descriptions, and download links.

### Quick Overview
- **Up**: Mission Control (show all windows)
- **Down**: App Exposé (current app windows) 
- **Left/Right**: Navigate between desktop spaces
- **Rock gestures**: Show Desktop and Launchpad (manual setup required)
