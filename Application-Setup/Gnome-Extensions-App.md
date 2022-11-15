# Gnome Extensions App

## Installation

Open Terminal, and run the following command to install Gnome Extensions:

```
sudo dnf install gnome-extensions-app
```

## Built-In Extensions

Disable the "Background Logo" extension and the "Launch new instance" extension. Enable Applications Menu and Places Status Indicator.

## Manually Installed Extensions

Download the following extensions from this [website](https://extensions.gnome.org), and configure them:

- "Allow Locked Remote Desktop" by jik@kamensus
- "Alphabetical App Grid" by stuarthayhurst
	- General settings
		- Position of ordered folders: Start
- "Autohide Volume" by t184256
- "Bedtime Mode" by ionutbortis
    - Automatic Schedule: On
        - Start Time: 21:00
        - End Time: 6:00
    - On-Demand
        - Show Button: On Active Schedule
        - Button Location: System Menu
- "Bing Wallpaper" by neffo (Currently Disabled)
    - Settings
        - Hide the indicator: On
    - Lock Screen
        - Override GDM3 lockscreen effects: On
        - Presets: GNOME default
    - Debug options
        - Always show new images: On (Use the tray icon to switch)
- "Blur My Shell
    - General
    - Panel
        - Panel blur: Off
- "Bring Out Submenu Of Power Off/Logout Button" by pratap@fastmail.fm
- "Burn My Windows" by Simme
    - Also Add Effects to Dialogs: On
    - Disable Fire and Glide when closing windows
    - Glide
        - Use this effect when opening windows: On
        - Use this effect when closing windows: On
        - Animating Time [ms]: 200 (or as close as you can get)
- "Caffeine" by eon
	- General
		- Enable for fullscreen apps: Off
        - Toggle shortcut: Shift+Super+C
	- Apps
		- Apps that trigger Caffeine
			- Pomodoro
- "Cleaner Overview" by gonza_11
- "Compiz alike magic lamp effect" by hermes83
    - Duration (ms): 250
- "Compiz windows effects" by hermes83
    - Spring: 10.0
    - Mass: 70
    - Maximize effect: Off
- "Custom Hot Corners - Extended" by GdH
    - Top-Left Hot Corner
        1. Show Activities Overview
    - Top-Right Hot Corner
        1. Show Activities Overview
    - Bottom-Left Hot Corner
        1. Show Activities Overview
    - Bottom-Right Hot Corner
        1. Show Activities Overview
- "Dash to Dock" by michele_g
    - Position and size
        - Intelligent autohide
            - Autohide: Off
            - Dodge windows: Off
    - Launchers
        - Show trash can: Off
        - Show volumes and devices: Off
    - Behaviour
        - Use keyboard shortcuts to activate apps
            - Number overlay: Off
            - Show the dock if it is hidden: Off
            - Shortcut for the options above: Blank
        - Click action: Minimize or show previews
            - Shift+Click action: Launch new instance
            - Middle-Click action: Quit
            - Shift+Middle-Click action: Quit
    - Appearance
        - Show overview on startup: Off
        - Customize opacity: Fixed
        - Opacity: 0%
- "Date Menu Formatter" by mkakubowski
	- Pattern: `EEE K:mm aaa'    '`
	- Font size: 10
- "Dell Command Configure menu" by vsimkus
- "Desktop Cube" by Simme
    - General Options
        - Transition time from desktop to overview [ms]: 250
        - Transition time between workspaces [ms]: 350
    - Overview Options
        - Opacity of active workspace: 100
        - Opacity of inactive workspaces: 0
- "GSConnect" by daniellandau
- "Hide Top Bar" by tuxor1337 (Currently disabled)
    - Sensitivity
        - Keep hotcorner sensitive, even in hidden state: On
    - Keyboard shortcuts
        - Key that triggers the bar to be shown: Super+T
        - Delay before the bar rehides itself after key press: 2.0
    - Intellihide
        - Only hide panel when a window takes the space: Off
- "Just Perfection" by JustPerfection
	- Profile
		- Profile: Default
	- Visibility
        - Activities Button: Off
		- App Menu: On
        - App Menu Label: On
		- World Clock:  Off
		- Weather: Off
		- Events: Off
		- Search: Off
        - Dash Separator: Off
		- Workspace Popup: Off
		- Workspace App Grid: Off
		- Window Picker Close Button: Off
        - Window Picker Caption: Off
		- Background Menu: Off
        - Ripple Box: Off
    - Icons
        - App Menu Icon: Off
        - Panel Notification Icon: Off
	- Behaviour
        - Window Demands Attention Focus
        - Double Super to App Grid: Off
		- Startup Status: Desktop
	- Customize
		- Panel Button Padding Size: 2px
        - Clock Menu Position: Right
        - Clock Menu Position Offset: 9
        - Workspace Switcher Size: 12%
		- OSD Position: Center
- "Logo Menu" by Aryan_K
    - Icon Settings
        - Icon: Choose corresponding grayscale OS icon
        - Icon Size: 18px
- "Maximize To Empty Workspace" by kaiseracm
- "Mouse Follows Focus" by LeonMatthes
- "Notification Timeout" by chlumskyvaclav
- "Overview Clicking" by mechtifs
- "Pano - Clipboard Manager" by alperenelhan
    - Open Terminal, and run the following to install dependencies: `sudo dnf install libgda libgda-sqlite`
    - History Length: 100
    - Global Shortcut: Super+V
    - Show Indicator: Off
- "Power Profiles Indicator" by krst
- "Sound Input & Output Device Chooser" by kgshank
    - General Settings
        - Integrate selector with slider: On
        - Hide selector if there's only one device: On
- "Tiling Assistant" by Leleat
	- General
		- Tile Groups
			- Raise together: Off
	- Keybindings
		- General
            - Toggle 'Always on Top': Super+W
            - Toggle Maximization: Super+S
            - Restore Window Size: Shift+Super+S
            - Move Window to Center: Shift+Ctrl+Super+S
		- Edge Tiling
			- Tile to top: Shift+Super+W
			- Tile to bottom: Shift+Super+X
			- Tile to left: Super+A
			- Tile to right: Super+D
		- Edge Tiling
			- Tile to top-left: Super+Q
			- Tile to top-right: Super+E
			- Tile to bottom-left: Super+Z
			- Tile to bottom-right: Super+C
    - Advanced
        - Default Window Movement Mode: Adaptive Tiling
        - Other Window Movement Settings
            - Restore Window Size on: Grab end
- "Unite" by hardpixel
    - It may be necessary to renable the titlebar buttons by running `gsettings reset org.gnome.desktop.wm.preferences button-layout` in Terminal
    - General
        - Extend top bar left box: Off
        - Show system tray in top bar: Off
        - Show desktop name in top bar: Off
        - Restrict functionalities to the primary screen: Off
        - Enable titlebar actions on top bar click: Off
        - Hide activities button: Always
        - Hide window titlebars: Always
        - Show window title in app menu: Never
        - Show window buttons in top bar: Never
        - Notifications messages position: Center
- "User Themes" by fmuellner
- "Volume Scroller" by trflynn89
- "Workspace Switcher Manager" by GdH
    - Pop-up
        - On-Screen Time (ms): 500
        - Fade Out Time (ms): 400
    - Size & Text
        - Global Scale (%): 125
    - Colors
        - Allow Custom Colors: On
            - Active WS Background color / opacity: #474747
    - Content
        - Pop-Up Active Workspace Indicator Content
            - Show Workspace Index: Off
        - Pop-Up Inactive Workspace Indicator Content
            - Show Workspace Index: Off

## GSConnect Setup

Open Terminal, and run the following command to solve connection issues: 

```
sudo dnf install openssl
```

Restart the computer, then connect any compatible devices.
