# Gnome Tweak Tool

## Installation

Open Terminal, and run the following command to install Gnome Tweak Tool:

```
sudo dnf isntall gnome-tweak-tool
```

## Theme Setup

Download and install the [McMojave GTK theme](https://github.com/vinceliuice/Mojave-gtk-theme), then open Terminal. Run the following:

```
./install.sh -i fedora -c dark -o standard -t default -a standard
```

Follow the GitHub instructions to install the Firefox theme. Customize `userChrome.css` and make the following changes:

- Hide the tab bar when only one tab is open
- Limit the URL bar's autocompletion popup's width to the URL bar's width
- Rounded title buttons
- Use system theme icons instead of Adwaita icons included by theme

Append the following to the end of `userChrome.css` to hide the list all tabs button:

```
@namespace url("http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul");

#tabbrowser-tabs ~ #alltabs-button {display:none!important;}
```

Delete lines 9-12 in `Mojave/parts/csd.css` to remove the rounded window corners.

Download the [McMojave cursors](https://www.gnome-look.org/p/1355701), and unzip the contents to `~/.local/share/icons/`

## Settings

Launch the program (Tweaks) and change the following settings:

- Appearance
    - Shell: Mojave-Dark
    - Cursor: McMojave-cursors
    - Legacy Applications: Mojave-Dark
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
