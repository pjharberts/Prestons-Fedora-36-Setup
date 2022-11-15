# Gnome Tweak Tool

## Installation

Open Terminal, and run the following command to install Gnome Tweak Tool:

```
sudo dnf isntall gnome-tweak-tool
```

## Theme Setup

Download and install the [McMojave GTK theme](https://github.com/vinceliuice/Mojave-gtk-theme), then open Terminal. Run the following:

```
./install.sh -i fedora -c dark -o solid -t grey -a standard -lr
```

Download the [McMojave cursors](https://www.gnome-look.org/p/1355701), and unzip the contents to `~/.local/share/icons/`

## Settings

Launch the program (Tweaks) and change the following settings:

- Appearance
    - Shell: Mojave-Dark-solid
    - Cursor: McMojave-cursors
    - Legacy Applications: Mojave-Dark-solid
- Keyboard & Mouse
	- Mouse
		- Pointer Location: On
- Startup Applications
    - Add "Start Syncthing"
- Windows
	- Center New Windows: On
    - Resize with Secondary-Click: On
	- Window Focus
		- Focus on Hover: On
