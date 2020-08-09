# About
**GMS2_RPC** is a Discord Rich Presence Module for GameMaker Studio 2.     
It is a small application that is to run in background and supply your Discord profile with Rich Presence containing information specific to GameMaker Studio 2 while it is running, as exemplified below.

![Rich Presence Status Preview](https://i.imgur.com/fWmYior.png)

The application is standalone and does not interact with GameMaker Studio 2 itself. It gathers all of its information from the process list and window title of GameMaker Studio 2 IDE.


# Features

* Uses Discord Rich Presence to display project name that is currently being open in GameMaker Studio 2 IDE, as well as the current session time.
* Supports multiple instances of the IDE running at the same time and focuses on ones that have a project open.
* Shows if you are currently running an application via the runner of GameMaker Studio 2 (when there is only one project open).
* Supports Beta builds of the GameMaker Studio 2 IDE.

* Configurable via the right-click context menu of its tray icon. Can setup autostart on system boot (using current user's registry) and permamently hide the tray icon.
* Left-clicking the tray icon will create a notification that displays the total uptime of GameMaker Studio 2 while this application was running.


# Usage

### Requirements

* Microsoft Windows 64-bit Operating System (Windows 7 or newer) with GameMaker Studio 2 and Discord installed.
* [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) (4.7.2 or newer).

### Initialization

1. Head to the [Releases](https://github.com/Git-Mtax/GMS2_RPC/releases) tab and download the lastest release.
2. Unpack the archive with the application to any folder on your hard drive.
3. Launch `GMS2_RPC.exe`. The application should create an icon in your tray and Discord Rich Presence should be set when you launch GameMaker Studio 2.


# Credits

The application was created by [Mtax](https://github.com/Git-Mtax).

The project uses the following libraries:     
* [discord-rpc-csharp](https://github.com/Lachee/discord-rpc-csharp)
* [ini-parser](https://github.com/rickyah/ini-parser)

GameMaker Studio 2 and its logo are a property of YoYo Games.    
Discord is a property of Discord, Inc.    
This is a third-party project not affiliated with either of them.
