# Gnome Extensions App

## Installation

Open Terminal, and run the following command to install Gnome Extensions:

```
sudo dnf install gnome-extensions-app
```

## Built-In Extensions

Disable the "Background Logo" extension and the "Launch new instance" extension.

## Manually Installed Extensions

Download the following extensions from this [website](https://extensions.gnome.org), and configure them:

- "Allow Locked Remote Desktop" by jik@kamensus
- "Alphabetical App Grid" by stuarthayhurst
	- General settings
		- Position of ordered folders: Start
- "Bedtime Mode" by ionutbortis
    - Automatic Schedule: On
        - Start Time: 21:00
        - End Time: 6:00
    - On-Demand
        - Show Button: On Active Schedule
- "Bing Wallpaper" by neffo
    - Settings
        - Indicator icon: low-frame-symbolic
    - Lock Screen
        - Override GDM3 lockscreen effects: On
        - Presets: GNOME default
    
- "Blur My Shell
    - General
    - Panel
        - Compatibility
            - Hidetopbar extension: On
- "Caffeine" by eon
	- General
		- Enable for fullscreen apps: Off
	- Apps
		- Apps that trigger Caffeine
			- Pomodoro
- "Cleaner Overview" by gonza_11
- "Clipboard Indicator" by Tudmotu
	- Remove whitespace around text: On
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
	- Pattern: `h:mm  EEEE, MMMM d'  '`
	- Font size: 11
- "Default Workspace" by MateusRodCosta
    - Edit metadata.json in the extenstion folder to correspond to Gnome 42
- "Dell Command Configure menu" by vsimkus
- "GSConnect" by daniellandau
- "Hide Top Bar" by tuxor1337
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
		- Acitivities Button: Off
		- App Menu: Off
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
        - Double Super to App Grid: Off
		- Startup Status: Desktop
	- Customize
		- Panel Button Padding Size: 2px
        - Workspace Switcher Size: 12%
        - Animation: Faster
		- OSD Position: Top Center
- "Mouse Follows Focus" by LeonMatthes
- "Notification Timeout" by chlumskyvaclav
- "Overview Clicking" by mechtifs
- "Overview Dash Hide" by rokenz05
- "Space Bar" by luchrioh
	- Behaviour
		- General
			- Switch workspaces with scroll whell: Over workspaces bar
	- Shortcuts
        - Move to workspace: Off
        - Open menu: Ctrl+Super+W
    - Rename the 3 workspaces as follows: Left, Primary, Right
- "Tiling Assistant" by Leleat
	- General
		- Tile Groups
			- Raise together: Off
	- Keybindings
		- General
            - Toggle 'Always on Top': Shift+Super+W
            - Toggle Maximization: Super+S
            - Restore Window Size: Shift+Super+S
            - Move Window to Center: Shift+Ctrl+Super+S
		- Edge Tiling
			- Tile to top: Super+W
			- Tile to bottom: Super+X
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
- "Volume Scroller" by trflynn89

## GSConnect Setup

Open Terminal, and run the following command to solve connection issues: 

```
sudo dnf install openssl
```

Restart the computer, then connect any compatible devices.
