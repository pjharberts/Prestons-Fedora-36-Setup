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
- "Blur my Shell" by aunetx
	- Overview
		- Background blur
			- Overview components style: Dark
- "Caffeine" by eon
	- General
		- Enable for fullscreen apps: Off
	- Apps
		- Apps that trigger Caffeine
			- Pomodoro
- "Cleaner Overview" by gonza_11
- "Clipboard Indicator" by Tudmotu
	- Remove whitespace around text: On
- "Date Menu Formatter" by mkakubowski
	- Pattern: `MMMM d  k:mm ' '`
	- Font size: 11
- "GSConnect" by daniellandau
- "Just Perfection" by JustPerfection
	- Profile
		- Profile: Default
	- Visibility
		- Panel: Off
		- Acitivities Button: Off
		- App Menu: Off
		- World Clock:  Off
		- Weather: Off
		- Events: Off
		- Search: Off
		- Dash: Off
		- Dash Separator: Off
		- Show Applications Button: Off
		- Workspace Popup: Off
		- Workspace Switcher: Off
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
- "Notification Timeout" by chlumskyvaclav
- "No Titlebar When Maximized" by alecdotninja
- "Overview Clicking" by mechtifs
- "Space Bar" by luchrioh
	- Behaviour
		- General
			- Switch workspaces with scroll whell: Over workspaces bar
	- Shortcuts
		- Shift+Super+1...0 Move to workspace: On
- "Tiling Assistant" by Leleat
	- General
		- Tile Groups
			- Raise together: Off
	- Keybindings
		- General
			- Toggle 'Always on Top': Shift+Super+T
		- Edge Tiling
			- Tile to top: Super+K
			- Tile to bottom: Super+J
			- Tile to left: Super+H
			- Tile to right: Super+L
		- Edge Tiling
			- Tile to top-left: Shift+Super+H
			- Tile to top-right: Shift+Super+J
			- Tile to bottom-left: Shift+Super+L
			- Tile to bottom-right: Shift+Super+K
- "Volume Scroller" by trflynn89

## GSConnect Setup

Open Terminal, and run the following command to solve connection issues: 

```
sudo dnf install openssl
```

Restart the computer, then connect any compatible devices.
