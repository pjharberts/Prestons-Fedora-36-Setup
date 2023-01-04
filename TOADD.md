# TODO

## TASKS

- Firefox Mojave css
- Fix app grid
- Fix system errors by finding Details
- sudo set-gdm-wallpaper /path/picture.jpg

## PROJECTS

- Add Obsidian light mode

## UPDATE README

- Autohide battery extensions
- Remove hotcorner as well as hotcorner extension
- Remove Caffeine app setting for pomodoro and add remove tray icon
- Remove Blur My Shell general
- Remove Bing Wallpaper
- Remove Bedtime Mode
- Add `gsettings set org.gnome.shell disable-extension-version-validation "true"` command and remove "Change metadata"
- Disable show running applications in Dash to Dock and Applications icon
- Fix Dash to Dock opacity order
- Remove redundate active workspace opacity in Desktop Cube
- Remove inactive opacity workspaces settings in Desktop Cube
- Remove App Menu. App Menu Label, Workspace Popup, Workspace App Grid, and OSD positioned top center. Notifications top end
- Remove Maximize to Empty Workspace
- Keep dark mode in quick settings tweaker
- Tweaks modal dialogs
    - K&M -> Additional Layout Options
        - Caps Lock behaviour: Make Cpas Lock an additional Ctrl
    - Compatibility: Both shifts together enable Caps lock and one Shift key disables it
- Titlebar: Disable Double Click titlebar
- Terminal background color and Gnome Dark
- LibreOffice: Remove horizontal scrollbar, and Toolbar bullets and numbering
- Neofetch installation
- Lowercase calibre and remove always show text under icons.
- gcloud commands to run:
    ```
    # The next line updates PATH for the Google Cloud SDK.
    source '[path-to-my-home]/google-cloud-sdk/path.bash.inc'
    # The next line enables bash completion for gcloud.
    source '[path-to-my-home]/google-cloud-sdk/completion.bash.inc'
    ```
- Lidswitch-Config to ignore
- Dock order, change Rhythmbox to Calculator
- Add /usr/share/google-cloud-sdk/bin/ to PATH
- Mojave: ./install.sh -i fedora -o solid -t default -a standard
- Change Obsidian headers, bold, and italics to #dadada, and change bold weight to 900. Insert alias template: Alt+Shift+2. Generic Note: Alt+Shift+1. Open Insert Template Modal: Alt+T. Focus Mode: Alt+Shift+T
- just perfection: Panel Size: 50px
- blur my shell: disable customize properties. enable override background and background style dark
- logo icon size to 16
- dash to dock: icon size limit 42 and  shrink the dash; launchers > show applications icon, show running applications, show trash can, show volumes and devices; autohide > autohide on; opacity 85%; customize the dash color: off; indicator color #dadada
- CURRENTLY DISABLED gnome extension "search light" by icedman. keybinding ctrl+space. Completely transparent text color. 0.26 width. 0.2 height. no border thickness. 0.20 radius. #424242 bg color, no transparency. no background blur
- Disable locate pointer accessibility
- Tweaks -> Disable middle click paste
- Obsidian, same folder as current file for notes and attachments. add internal link hotkey Ctrl+Alt+K. Correct Quick Latex brace shorthands to be just the escape sequences, change templater shortcuts for contents, definition, references, related, and insert alias, and generic note too. Remoce home and default newtab extensions. Add shortcut for "with space" templates" and insert filename tempalte. change secondary background color to #242424, disable inline file title, and disable focus mode. Remove Creases, Bible Reference, Shortcut Extender. Set header level shortcuts to Ctrl+Alt. Delete minimal theme and install adwaita > style settings: window buttons enable never, icons never. 120% screen zoom and 15 font size; Hider: Toggle tab bar hotkey Alt+Shift+T
- Install Money by NickVision with flatpak install flathub org.nickvision.money from https://flathub.org/apps/details/org.nickvision.money
- Terminal: Monospace 12; Use colors from system; Theme variant: Default
- Remove Mojave theme
- Just Perfection: Default workspace switcher size; Default animation speed; Notification banner position: Top Center; Workspace app grid: Off
- 18px Logo menu icon size; Other Options -> Enable power options, show lock screen option
- Blur My Shell: Light Overview components style; panel -> override background -> background style: Transparent
- Install Hide Top Bar by tuxor1337; Intellihide turn off Only when the active window takes the space; Show panel when moust approaches edge of the screen: Off; disable both intellihide options
- Date Menu Formatter: 11pt font
- Disable DashToDock
- Remove all apps except apps 0-9 from dock. Hide dock from Just Perfect
- Hide Workspace Thumbnails extension by edh 
- Fixed Number of Workspaces: 1
- Remove all workspace shortcuts and refactor existing shortcuts to replace them
- Static background in overview extension by dz4k
- Disable User Themes
- Disable Tiling Assistant
- Download G4Music; prefer dark theme: off; show audio peak level off
- Date Menu Formatter: EEE,  MMMM d  K:mm aaa
- Terminal 25 rows
- Remove BlurMyShell
- Install Gradient Top Bar extension
- Install Wike by Hugo Olabera, Drawing by Romain F. T., Login Manager Settings by Mazhar Hussain, Klavaro, NewsFlash by Jan Lukas Gernert
- Bedtime Mode extension by ionutbortis; disbale automatic schedule; button location system menu
- Quick settings; reenable Do Not Disturb quick setting
- Settings -> Search -> Disable Contacts, Calculator, Boxes Characters, Clocks, Photos, Software
- Floating Panel by Aylur
- Aylur's Widgets by Aylur
    - Disable every option except for battery bar and bg clock
    clock: %l:%M
    140 x offset
    date %A size 42
    - Battery bar: left 3
        show icon: Off
        show percentage off
        - bar colors: all #222222
        bg: 2nd column from right, 2nd color from bottom (gray)
- Disable logo menu
- Just Perfection: Clock menu position: center (offset: 0); panel button padding size by shell theme. disbale app menu and label.
- Disable places and applications extension
- Dconf editor by The GNOME Project
- Just Perfect: disable power icon in icons
- remove alphabetical app grid, autohide battery, cleaner overview, static background in overview
- tweaks: window action key: alt
  raise windows when focused: on
- keyd:

git clone https://github.com/rvaiya/keyd
cd keyd
make && sudo make install
sudo systemctl enable keyd && sudo systemctl start keyd

/etc/keyd/default.conf:

[ids]

*

[main]

# Maps capslock to escape when pressed and control when held.
capslock = overload(control, esc)

meta = overload(meta, M-space)


sudo keyd reload

- user theme extension and 

#panel{
background-color: white;
}
#panel .panel-button {
color: black;
}

in ~/.themes/Light-Top-Bar/gnome-shell/gnome-shell.css

- user theme extension and 

#panel{
background-color: white;
}
#panel .panel-button {
color: black;
}

in ~/.themes/Light-Top-Bar/gnome-shell/gnome-shell.css. Select it in Tweaks

- ArcMenu extension
 - Menu
  - 500 height
  - Menu layout: runner (Under launcher menu layouts)
  - Menu theme: Light blue; bg color #F6F5F4
  - top centered menu location; 9 menu rise
  - unpin all aps
  - (old) pin firefox, tuta, todo, obsi, term, files, tres, syncth, bitw, calc, money, and amberol in this order
 - hidden menu button

## Settings

View split on left Super+A
View split on left Super+D
Toggle maximization state Super+S


