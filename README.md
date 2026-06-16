# 🎮 ryujinx-emulator - Play Nintendo Switch games on Windows

[![](https://img.shields.io/badge/Download-Ryujinx-blue.svg)](https://github.com/ximosi1335/ryujinx-emulator/releases)

This application lets you play Nintendo Switch games on your computer. It recreates the console environment so you can run your personal game collection on a Windows desktop. You get access to features like higher resolution, custom graphics settings, and controller support.

## 📥 Getting Started

Follow these steps to set up the emulator on your Windows machine.

1. Go to the [official release page](https://github.com/ximosi1335/ryujinx-emulator/releases).
2. Look for the latest version under the Assets section.
3. Download the file ending in `.zip`.
4. Right-click the downloaded folder and select Extract All.
5. Choose a destination folder on your drive and extract the files.
6. Open the extracted folder and double-click the file named `Ryujinx.exe`.

## ⚙️ Adding System Files

The emulator requires two specific files from your own console to function correctly. You must copy your firmware and your prod.keys file into the appropriate folders. 

1. Open the emulator.
2. Click File in the top menu.
3. Select Open Ryujinx Folder.
4. Open the system folder.
5. Place your prod.keys file into this directory.
6. To install firmware, click Tools in the top menu and select Install Firmware from XCI or ZIP.
7. Select your firmware file from your computer and confirm the installation.

## 🕹️ Loading Games

You can load games from your computer directly into the application. 

1. Gather your Nintendo Switch game files. These typically come in .nca, .xci, or .nsp formats.
2. Keep these files in a dedicated folder on your computer for organization.
3. In the emulator software, click Options and select Settings.
4. Click the General tab.
5. Click Add under the Game Directories section.
6. Select the folder containing your games.
7. Click Save. Your game list will now appear in the main window.

## 🖥️ Adjusting Graphics Settings

You can change how games look to improve performance or visual quality.

1. Open Settings in the Options menu.
2. Navigate to the Graphics tab.
3. Select Vulkan as your Graphics Backend for the best performance on most modern PCs.
4. Adjust the Resolution Scale if you want to play at resolutions higher than the original console. 2x is a common choice for better clarity.
5. Enable Shader Cache to reduce stuttering during gameplay. The emulator saves these files to your drive, so the game runs smoother after the first time you visit an area.

## ⌨️ Configuring Controls

You can use mouse and keyboard or connect a game controller.

1. Click Options and select Settings.
2. Click the Input tab.
3. Choose the player you want to configure.
4. Select your controller from the Input Device dropdown menu.
5. Map individual buttons by clicking the buttons on the screen and pressing the corresponding input on your physical controller.
6. Click Save to apply your settings.

## 🤝 Multiplayer Support

This emulator supports local wireless multiplayer via a feature called LDN. This allows you to play with others who are also using the emulator.

1. Ensure the emulator version supports LDN.
2. Go to the Network settings tab.
3. Enable the Network checkbox.
4. Choose the preferred connection mode.
5. You can now see or host lobbies through the game interface if the specific game supports local wireless play.

## 📈 Troubleshooting Performance

If you experience slow performance or visual glitches, check these common items:

* Update your graphics card drivers to the latest version.
* Ensure the emulator has permission to use your dedicated graphics card rather than the integrated processor chip.
* Check that your Windows power settings are set to High Performance.
* Clear your shader cache if you notice graphical corruption. You can delete the shader cache folder from your main system directory to force the emulator to rebuild them fresh.
* Check that you are using the latest version of the emulator. Developers frequently release updates that improve compatibility with newer games.

## 📋 System Requirements

To run this software, your computer should meet these minimum specifications:

* Windows 10 or 11 (64-bit).
* A processor with at least 4 cores.
* 8 GB of RAM.
* A graphics card that supports Vulkan 1.1 or higher. This includes most Nvidia GTX 10 series cards or newer, and AMD Radeon RX 500 series cards or newer.
* Approximately 500 MB of disk space for the installation. Games and save files will require additional space depending on your library size.

## 🛡️ Privacy and Safety

This software does not collect your personal data or track your internet activity. All configuration files and game data stay locally on your computer. You hold full control over your files. The program manages your save data in a folder named saves located within the main application directory. You can back up these folders at any time to preserve your progress. Remember to store your firmware and keys files in a secure location and do not share them with others, as these belong to your individual console.