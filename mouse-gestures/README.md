# macOS Mouse Gestures Setup

This repository contains a collection of AppleScript files for enhancing macOS productivity through mouse gestures using **xGestures**.

## About xGestures

[xGestures](https://briankendall.net/xGestures/download.htm) is a powerful mouse gesture application for macOS that allows you to perform various actions by drawing simple patterns with your mouse or trackpad.

### Download xGestures

- **Latest Version (1.9.2)**: [xGestures1.9.2.dmg](https://briankendall.net/xGestures/download.htm) - Compatible with macOS 10.9 and later, including Ventura and Sonoma
- **Legacy Version (1.7.8)**: Available for macOS 10.7 and 10.8

> **Note**: xGestures is now freeware and no longer actively developed, but remains fully functional on modern macOS versions.

## Gesture Scripts

This setup includes four main gesture scripts that enhance your macOS workflow:

### 📁 Included Scripts

| Script | Gesture | Function | Description |
|--------|---------|----------|-------------|
| `up.scpt` | ↑ | Mission Control | Shows all open windows across all desktops (Exposé) |
| `down.scpt` | ↓ | App Exposé | Shows all windows of the currently active application |
| `left.scpt` | ← | Previous Desktop | Navigates to the previous desktop space (Control + ←) |
| `right.scpt` | → | Next Desktop | Navigates to the next desktop space (Control + →) |

### 🎯 Gesture Functions

#### **Up Gesture** - Mission Control
- **Action**: Triggers Mission Control (Exposé all windows)
- **Equivalent**: F3 key or Control + ↑
- **Use Case**: Get an overview of all open windows across all desktop spaces

#### **Down Gesture** - Application Windows
- **Action**: Shows all windows of the current application
- **Equivalent**: Control + ↓
- **Use Case**: Quickly switch between windows of the same app

#### **Left Gesture** - Previous Desktop
- **Action**: Switches to the previous desktop space
- **Equivalent**: Control + ← arrow key
- **Use Case**: Navigate backwards through your desktop spaces

#### **Right Gesture** - Next Desktop
- **Action**: Switches to the next desktop space
- **Equivalent**: Control + → arrow key
- **Use Case**: Navigate forwards through your desktop spaces

## Manual Configuration Required

After installing xGestures and importing these scripts, you'll need to manually configure two additional gestures:

### 🪨 Rock Gestures (Manual Setup)

1. **Rock Left** → **Show Desktop**
   - Gesture: Rock left (move mouse left then right quickly)
   - Action: Show Desktop (F11 or Mission Control → Desktop)
   - Use Case: Quickly access desktop and files

2. **Rock Right** → **Launchpad**
   - Gesture: Rock right (move mouse right then left quickly)
   - Action: Open Launchpad to show all applications
   - Use Case: Quick access to all installed applications

## Installation & Setup

1. **Download and Install xGestures**
   - Download from [Brian Kendall's website](https://briankendall.net/xGestures/download.htm)
   - Install the application and grant necessary permissions

2. **Import Gesture Scripts**
   - Open xGestures preferences
   - Import the provided `.scpt` files for each gesture direction
   - Configure the gesture sensitivity to your preference

3. **Configure Rock Gestures**
   - Manually set up Rock Left for Show Desktop
   - Manually set up Rock Right for Launchpad

4. **System Permissions**
   - Ensure xGestures has Accessibility permissions in System Preferences
   - Allow the app to control your computer for gestures to work

## Usage Tips

- **Gesture Sensitivity**: Adjust in xGestures preferences to match your mouse/trackpad usage
- **Practice**: Start with simple up/down gestures before moving to more complex patterns
- **Customization**: Feel free to modify the AppleScript files to suit your workflow
- **Backup**: Keep a backup of your gesture configuration for easy restoration

## Troubleshooting

- **Gestures not working**: Check System Preferences → Security & Privacy → Accessibility
- **Scripts not executing**: Ensure AppleScript files are properly compiled and imported
- **Performance issues**: Adjust gesture recognition sensitivity in xGestures preferences

---

*This setup enhances macOS productivity by providing intuitive mouse gestures for common window management and navigation tasks.*