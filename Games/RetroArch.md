# RetroArch

## Installation

Open Terminal, and run the following to install RetroArch (Flatpak):

```
flatpak install --user flathub org.libretro.RetroArch
```

## Settings

- Video
    - Fullscreen Mode
        - Start in Fullscreen Mode: On
        - Window Fullscreen Mode: Off
- Saving
    - Sort Saves into Folders by Core Name: On
    - Sort Save States into Folders by Core Name: On
    - Auto Save State: On
    - Load State Automatically: On
    - SaveRAM Compression: On
- File Browser
    - Filter Unknown Extensions: Off
    - Use Built-In Media Player: Off
    - Use Built-In Image Viewer: Off
    - Remember Last Used Start Directory: On
- On-Screen Display
    - On-Screen Notifications
        - Notification Visibility
            - "Load Content" Startup Notification: Off
            - Input (Autoconfig) Connection Notifications: Off
            - Input Remap Loaded Notifications: Off
            - Config Override Loaded Notifications: Off
- User Interface
    - Menu Item Visibility
        - Quick Menu
            - Show 'Start Streaming': Off
            - Show 'On-Screen Overlay': Off
            - Show 'Video Layout': Off
            - Show 'Latency': Off
            - Show 'Rewind': Off
            - Show 'Cheats': Off
        - Show 'Load Core': Off
        - Show 'Load Disc': Off
        - Show 'Dump Disc': Off
        - Show 'Help': Off
        - Show 'Images': Off
        - Show 'Music': Off
        - Show 'Videos': Off
        - Show 'Explore': Off
        - Show 'Standalone Cores': Off
        - Style of Date and Time: HH:MM (AM/PM)
        - Show Core Name: Off
    - Appearance
        - Menu Scale Factor: 0.90x (or whatever is comfortable)
- Playlists
    - Truncate Playlist Names (Restart Required): Off
- User
    - Username: Set desired username
- Directory
    - File Browser: /home/username/Games/Emulation

## Cores

Open the Online Updater, and open Core Downloader. Download the following cores:

- NEC - PC Engine / SuperGrafx / CD (Beetle PCE)
- Nintendo - DS (DeSmuMe)
- Nintendo - Game Boy / Color (Gambatte)
- Nintendo - Game Boy Advance (mGBA)
- Nintendo - GameCube / Wii (Dolphin)
- Nintendo - NES / Famicon (Nestopia UE)
- Nintendo - Nintendo 64 (ParaLLEl N64)
- Nintendo - SNES / SFC (Snes9x - Current)
- Sega - MS/GG/MD/CD (Genesis Plus GX)
- Sony - PlayStation (Beetle PSX HW)

## Online Updater

Go to the Online Updater, and select all options that begin with "Update" to fetch necessary updates.

## Import Content

Go to the Import Content tab, and select Scan Directory. Navigate to any directory with games or subdirectories with games, and scan it. Adjust the playlists as follows from each systems' Playlist settings:

- Nintendo - Nintendo Entertainment System
    - Default Core: Nintendo NES / Famicon (Nestopia UE)
    - Label Display Mode: Remove () and []
- Sega - Mega Drive - Genesis
    - Default Core: Sega - MS/GG/MD/CD (Genesis Plus GX)
    - Label Display Mode: Remove () and []

## Nestopia UE

Open Quick Menu while in a game with this core loaded, and change the following settings:

- Shaders
    - Video Shaders: On
    - Remmeber Last Used Shader Directory: On
    - Load
        - shaders_glsl/crt/crt-hylian-multipass.glslp
    - Save
        - Save Core Preset

## Genesis GX

Open Quick Menu while in a game with this core loaded, and change the following settings:

- Shaders
    - Video Shaders: On
    - Remmeber Last Used Shader Directory: On
    - Load
        - shaders_glsl/crt/crt-hylian-multipass.glslp
    - Save
        - Save Core Preset
