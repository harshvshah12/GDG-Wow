# Flutter Setup Guide

This guide will help you set up your development environment for the Flutter workshop.

## System Requirements

- **Operating System**: Windows 10/11, macOS 10.15+, or Linux
- **Disk Space**: 2.5 GB (excluding IDE/tools)
- **Tools**: Git

## Installation Steps

### 1. Install Flutter SDK

#### Windows
1. Download the [Flutter SDK](https://flutter.dev/docs/get-started/install/windows)
2. Extract the zip file to a desired location (e.g., `C:\flutter`)
3. Add Flutter to your PATH:
   - Add `C:\flutter\bin` to your PATH environment variable

#### macOS
1. Download the [Flutter SDK](https://flutter.dev/docs/get-started/install/macos)
2. Extract the zip file to a desired location:
   ```bash
   cd ~/development
   unzip ~/Downloads/flutter_macos_3.19.0-stable.zip
   ```
3. Add Flutter to your PATH:
   ```bash
   export PATH="$PATH:`pwd`/flutter/bin"
   ```
4. Add the above line to your shell profile (`.zshrc` or `.bash_profile`)

#### Linux
1. Download the [Flutter SDK](https://flutter.dev/docs/get-started/install/linux)
2. Extract the tarball:
   ```bash
   cd ~/development
   tar xf ~/Downloads/flutter_linux_3.19.0-stable.tar.xz
   ```
3. Add Flutter to your PATH:
   ```bash
   export PATH="$PATH:`pwd`/flutter/bin"
   ```
4. Add the above line to your shell profile (`.bashrc` or similar)

### 2. Install an IDE

Choose one of the following:

#### Visual Studio Code (Recommended for beginners)
1. Download and install [VS Code](https://code.visualstudio.com/)
2. Install the Flutter and Dart extensions:
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
   - Search for "Flutter" and install the official Flutter extension

#### Android Studio / IntelliJ IDEA
1. Download and install [Android Studio](https://developer.android.com/studio) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
2. Install the Flutter and Dart plugins:
   - Open Android Studio / IntelliJ IDEA
   - Go to Preferences > Plugins
   - Search for "Flutter" and install the plugin
   - Restart the IDE when prompted

### 3. Setup a Device

Choose one of the following:

#### Physical Device
- **Android**: Enable USB debugging in Developer options
- **iOS**: Connect your device and trust the computer

#### Emulator/Simulator
- **Android**: Use AVD Manager in Android Studio to create a virtual device
- **iOS** (macOS only): Install Xcode and set up a simulator

### 4. Verify Installation

Run the following command to check if everything is installed correctly:

```bash
flutter doctor
```

Address any issues reported by `flutter doctor` before the workshop.

## Troubleshooting

If you encounter any issues during setup, please:

1. Check the [Flutter troubleshooting guide](https://flutter.dev/docs/get-started/install/troubleshoot)
2. Search for your issue on [Stack Overflow](https://stackoverflow.com/questions/tagged/flutter)
3. Contact the workshop organizers for assistance before the event

We look forward to seeing you at the workshop!