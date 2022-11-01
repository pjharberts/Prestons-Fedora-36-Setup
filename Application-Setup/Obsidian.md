# Obsidian

## Install

- Install with ```flatpak install flathub md.obsidian.Obsidian```

## Vault Setup

- Create and open vault in ```~/Obsidian/```

## Options

- Editor
	- General
		- Show indentation guides: Off
	- Advanced
		- Vim key bindings: On
- Files & Links
	- Confirm file deletion: Off
	- Automatically update internal links: On
	- Default location for new notes: Create folder and enter "Inbox"
    - New link format: Absolute path in vault
	- Detect all file extensions: On
	- Default location for new attachments: In the folder specified below
    - Attachment folder path: Attachments
	- Excluded files: Create folder and enter "Templater"
- Appearance
	- Font
		- Quick font size adjustment: Off
	- Advanced
		- Show inline title: Off
		- Show tab title bar: Off
- Hotkeys
	- "Templates: Insert template": Ctrl+T
	- Navigate back: Alt+Left
	- Navigate forward: Alt+Right
	- Toggle left sidebar: Ctrl+Shift+H
	- Toggle right sidebar: Ctrl+Shift+L
	- Toggle numbered list: Ctrl+Shift+[
	- Toggle bulleted list: Ctrl+Shift+]
	- Remove "New tab" default
	- "Daily notes: Open today's daily note": Ctrl+Shift+D
    - Split down: Alt+J
    - Split right: Alt+L
    - Focus on tab group above: Alt+K
    - Focus on tab group below: Alt+J
    - Focus on tab group to the left: Alt+H
    - Focus on tab group to the right: Alt+L

## Core Plugins

- Daily notes
	- Date format: YYYYMMDD
	- New file location: Create folder and enter "Daily"
- Quick switcher
	- Show all file types: On
- Turn off the Templates plugin

## Community plugins

Turn on community plugins and click Browse. Install and enable the following plugins, and configure them after having them all installed.

- "Advanced Tables" by Tony Grosinger
- "Bible Linker" by Jakub Kuchejda
    - Defaults
        - Link type default value: Embedded
- "Bible Reference" by tim-hub
	- Default Bible Version: "English - English Standard Version @Bolls Life"
- "Copy button for code blocks" by Daniel Brandenburg
- "Editory Syntax Highlight" by death_au
- "Excalidraw" by Zsolt Viczian
	- Excalidraw folder: Blank
	- (!) Excalidraw template file: Templates/Template.excalidraw
	- Filename
	  - Custom text after markdown Note's name when embedding: Make sure it is blank and there is no space
	  - Filename Date: Blank
	- Display
	  - Left-handed mode: On
	  - New drawing to match Obsidian theme: On
	  - Existing drawings to match Obsdian theme: On
	  - Excalidraw to follow when Obsidian Theme changes: On
	- Links and translusion
	  - Parse todo: On
	- Embed & Export
	  - Excalidraw preview to match Obsidian theme: On
	- Export Settings
	  - Export both dark- and light-themed image: On
	- Go to Hotkeys in Options and change the following:
		- Excalidraw: Create a new drawing - IN THE CURRENT ACTIVE PANE - and embed into active document: Ctrl+M
		- Excalidraw: Create a new drawing - IN A NEW PANE - and embed into active document: Ctrl+Shift+M
- "Find and replace in selection" by Dmitry Savosh
- "Footnote Shortcut" by Alexis Roneau, Micha Brugger
- "Hider" by @kepano
    - Hide app ribbon
    - Hide tab bar
	- Hide status bar: On
	- Hide vault name: On
    - Hide scroll bars: On
    - Hide sidebar toggle buttons: On
	- Hide metadata block in Reading View: On
- "Homepage" by mirnovov
	- Homepage: Create file and enter "Home"
	- Set the hotkey for "Homepage: Open homepage" to Ctrl+Shift+O
- "Obsidian Better Internal Link Inserter" by Salmund
	- Remove the shortcut for "Insert Markdown Link" and change "Obsidian Better Internal Link Inserter: Insert an internal link" to Ctrl+K
- "QuickShare" by Maxime Cannoodt (@mcndt)
- "Quick Latex for Obsidian
- "Shortcuts extender" by kitchenrunner
- "Sort & Permute lines" by Vinzent
- "Tag Wrangler" by PJ Eby
- "Templater" by SilentVoid
	- Template folder location: Templates
	- Remove and change the hotkey for "Templater: Open Insert Template Modal" to Ctrl+T

## Fix heading shortcuts

1. Remove all "Shortcuts extender: Shortcut for symbol" that are bound to Alt as well as "Shortcuts extender: Shortcut for code fences (\`)"
2. Remove the defaults for "Go to tab#number" and change to Alt+number

## Graph View

- Filters
	- Tags: On
	- Existing files only: On
- Forces
	- Repel force: 12.50
