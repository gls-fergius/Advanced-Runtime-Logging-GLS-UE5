# Game Logs System (GLS) Demo
![Unreal Engine Version](https://img.shields.io/badge/UE-5.2%20%7C%205.3%20%7C%205.4%20%7C%205.5-blue)

# Description
**Game Logs System (GLS)** is a plugin for Unreal Engine, designed for programmers and testers to help analyze logs both in the editor and at runtime during program execution on any device and platform. GLS allows you to collect logs from both the game and the engine, filter them by categories, classes, objects or custom tags.

The main goal of the plugin is to provide the ability to analyze logs on any platform in real time. Control is possible from the keyboard, joystick or touchpad.
The plugin is designed with an emphasis on high performance and ease of use, despite the potential large number of logs in the system.

The plugin is suitable for both small indie games and large AAA studios with a high load.

# Description of the Demo
The demo version of GLS is intended for use on Windows, available only in development and debug builds. The source code is not available, and it cannot be compiled independently. The demo version works in the editor and in built games.
Important: The demo version of the GLS plugin is compatible only with the engine downloaded from the Epic Games Launcher. The plugin will not work with a version of the engine compiled from source.

NOTE: After purchasing the full version, please manually delete the demo version from the engine folder. The Fab version and the demo version cannot exist in the engine at the same time.

You can also try the [example demo build](https://drive.google.com/drive/folders/1khDViXzgYJkmTye6xRB3smmi_8WPFli0?usp=sharing) in the assembled build together with the Lyra Game project.

You can also [download](https://drive.google.com/drive/folders/1R4LvuNhNuIRO7wzkGty7Yvl-XrLf38ig?usp=sharing) the demo plugin from Google Drive instead of cloning it.

# Installation
Follow these steps to install the demo plugin to Engine:

1. Clone the repository to your local machine. Attention: Please clone the repository instead of downloading the ZIP archive. If you download the archive, the plugin will not work because the compiled libraries will be missing.

2. Select the appropriate zip for your Unreal Engine version (e.g., 5.2, 5.3, 5.4, or 5.5).

3. Unzip and copy the plugin files to the following directory: **\Engine\Plugins\Marketplace\GameLogsSystem**
(Ensure the folder structure matches this path in your Unreal Engine installation directory.)
Attention, the plugin must be placed in the engine, not in your project. If you place it in the project, not in the engine, you will not be able to run the project, because the plugin is distributed without the source code.

4. Attention: You need to update the engine to the latest stable version. It will not work with preview versions.

5. Open the Unreal Editor.
Go to Edit -> Plugins. Locate "Game Logs System (GLS)" in the list and enable it. Restart the editor.

# Game Logs System (GLS) full version
[Fab marketplace link](https://fab.com/s/43bbed079742)

Full Version of GLS is available for all platforms, supports independent compilation, has source code and has no usage restrictions.

# Quick Start Guide
1. Enable the GLS plugin and start PIE or built game.
3. To open the GLS overlay in the editor or during gameplay, press and hold Alt + Shift + G.  
4. To open the overlay on a mobile device, press and hold two fingers on an empty area of the screen.
5. To open the overlay on a console, press and hold the Gamepad Special Right button.  

# License
This plugin is provided for evaluation purposes only. The GLS plugin distributed without the source code.

# Support
[Documentation](https://dev.epicgames.com/community/learning/tutorials/m36v/unreal-engine-fab-game-logs-system-gls-real-time-log-management-for-shipping-builds-on-mobile-and-console-platforms)
[gamelogssystem@gmail.com](gamelogssystem@gmail.com)

# Product stage
The product is in beta testing.
