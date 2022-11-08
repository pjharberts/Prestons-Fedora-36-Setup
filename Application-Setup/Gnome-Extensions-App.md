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
- "Dash to Dock" by michele_g
    - Position and size
        - Intelligent autohide
            - Dodge windows: Off
    - Behaviour
        - Use keyboard shortcuts to activate apps
            - Number overlay: Off
            - Show the dock if it is hidden: Off
            - Shortcut for the options above: `<Super>b`
        - Click action: Minimize or show previews
    - Appearance
        - Shrink the dash: On
        - Show overview on startup: Off
        - Use built-in theme: On    
- "Date Menu Formatter" by mkakubowski
	- Pattern: `h:mm  EEE, MMMM d'  '`
	- Font size: 11
- "Dell Command Configure menu" by vsimkus
- "GSConnect" by daniellandau
- "Hide Top Bar" by tuxor1337
    - Sensitiity
        - Show panel when mouse approaches edge of the screen: On
    - Keyboard shortcuts
        - Key that triggers the bar to be shown: Super+T
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
		- Workspace Popup: Off
		- Workspace App Grid: Off
		- Window Picker Close Button: Off
		- Background Menu: Off
	- Behaviour
		- Double Super to App Grid: Off
		- Startup Status: Desktop
	- Customize
		- Panel Button Padding Size: 2px
		- OSD Position: Top Center
- "Mouse Follows Focus" by LeonMatthes
- "Mpris Label" by moon-0xff
    - Left padding: 0
    - Visible fields and order: title; none; none
- "Notification Timeout" by chlumskyvaclav
- "No Titlebar When Maximized" by alecdotninja
- "Overview Clicking" by mechtifs
- "Space Bar" by luchrioh
	- Behaviour
		- General
			- Switch workspaces with scroll whell: Over workspaces bar
	- Shortcuts
        - Open menu: Ctrl+Super+W
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
- "Volume Scroller" by trflynn89

## GSConnect Setup

Open Terminal, and run the following command to solve connection issues: 

```
sudo dnf install openssl
```

Restart the computer, then connect any compatible devices.
