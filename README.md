# NBA LIVE 2005-08 Windowed Mode

This plugin allows user to toggle windowed mode in NBA Live 2005-08 without any external application.

## Installation

- Download the fixed executable for the game you would prefer windowed mode from [here](https://forums.nba-live.com/downloads.php?cat=263).

- Download [ASI Loader](https://forums.nba-live.com/downloads.php?view=detail&df_id=13583) and follow instructions in Installation section at its Readme file.

- Make sure you have the latest release from Releases.

- Copy "d3d9.dll", "oledlg.dll" and "plugins" folders from the archive to your game's root folder.
Otherwise, this plugin will not work.

- Copy "plugins" folder and "wndmode.ini" file to your game's root folder.

## Building on Windows

- Install [Visual Studio 2017/2022](https://visualstudio.microsoft.com/vs/community/) to your PC. It uses Visual Studio Installer. Community version is free and you can use that one. Check Game development with C++ and Desktop development with C++ options while installing

- Install **C++ Windows XP Support for VS 2017 (v141)** from Individual components tab at Visual Studio Installer.

- Install [Windows 8.1 SDK](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/)

- Check **Developers** section from ASI Loader’s readme. Apply the instructions. You can change output path and library paths, depending on where you place. To do so, you can extract the zip content directly. Extract the zip content (extract all).

- Clone the repository on your local and build the project using Visual Studio.

## Credits

- Dmitri (helping me with coding this, developer of FIFAM ASI Loader)