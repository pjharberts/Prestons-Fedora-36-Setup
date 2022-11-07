# Obsidian

## Install

- Install with ```flatpak install flathub md.obsidian.Obsidian```

## Vault Setup

- Create and open vault in ```~/Obsidian/```

## Options

- Editor
    - Display
		- Show indentation guides: Off
	- Advanced
		- Vim key bindings: On
- Files & Links
	- Confirm file deletion: Off
	- Automatically update internal links: On
	- Default location for new notes: Same folder as current file
    - New link format: Absolute path in vault
	- Detect all file extensions: On
	- Default location for new attachments: In the folder specified below
    - Attachment folder path: Inbox
	- Excluded files: Create folder and enter "Templates"
- Appearance
    - Theme: Click "Manage" and install the "Minimal" theme by @kepano
	- Font
		- Quick font size adjustment: Off
	- Advanced
		- Show inline title: Off
		- Show tab title bar: Off
- Hotkeys
	- "Templates: Insert template": Ctrl+T
	- Navigate back: Alt+Left
	- Navigate forward: Alt+Right
	- Toggle left sidebar: Alt+Q
	- Toggle right sidebar: Alt+Z
	- Toggle numbered list: Ctrl+Shift+[
	- Toggle bulleted list: Ctrl+Shift+]
	- Remove "New tab" default
	- "Daily notes: Open today's daily note": Ctrl+Shift+D
    - Split down: Alt+C
    - Split right: Alt+E
    - Focus on tab group above: Alt+W
    - Focus on tab group below: Alt+X
    - Focus on tab group to the left: Alt+A
    - Focus on tab group to the right: Alt+D

## Core Plugins

- Daily notes
	- Date format: YYYYMMDD
	- New file location: Create folder and enter "Daily"
- Page preview
    - Require CTRL to trigger page preview on hover
        - Reading view
- Quick switcher
	- Show all file types: On
- Turn off the Templates plugin

## Community plugins

Turn on community plugins and click Browse. Install and enable the following plugins, and configure them after having them all installed.

- "Advanced Tables" by Tony Grosinger
- "Audio Speed Plugin" by kaizau
    - Audio Speed Settings
        - Audio Playback Speed: 1 (change when needed)
- "Bible Linker" by Jakub Kuchejda
    - Defaults
        - Link type default value: Embedded
- "Bible Reference" by tim-hub
	- Default Bible Version: "English - English Standard Version @Bolls Life"
- "Copy button for code blocks" by Daniel Brandenburg
- "Editory Syntax Highlight" by death_au
- "Easy Typing" by yaozhuwa (Currently disabled)
    - Convert Rule (add the following rules)
        - " i |"; " I |";
    - Exclude Folders/Files
        - Exclude Folders/Files: Templates
- "Excalidraw" by Zsolt Viczian
	- Excalidraw folder: Blank
	- (!) Excalidraw template file: Templates/Template.excalidraw
	- Filename
        - Custom text after markdown Note's name when embedding: ` Drawing`
        - Filename Date: Blank
        - .excalidraw.md or .md: Off
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
    - Hide app ribbon: On
	- Hide status bar: On
	- Hide vault name: On
    - Hide scroll bars: On
    - Hide sidebar toggle buttons: On
	- Hide metadata block in Reading View: On
- "Homepage" by mirnovov
	- Homepage: Create file and enter "Home"
	- Set the hotkey for "Homepage: Open homepage" to Ctrl+Shift+O
- "Minimal Theme Settings" by @kepano
    - Features
        - Underline internal links: Off
		- Underline external links: Off
    - Hotkeys
        - Minimal Theme Settings: Toggle focus mode: Alt+T
- "Obsidian Better Internal Link Inserter" by Salmund
	- Remove the shortcut for "Insert Markdown Link" and change "Obsidian Better Internal Link Inserter: Insert an internal link" to Ctrl+K
- "QuickShare" by Maxime Cannoodt (@mcndt)
- "Quick Latex for Obsidian
- "Shortcuts extender" by kitchenrunner
- "Sort & Permute lines" by Vinzent
- "Style Settings" by mgmeyers
	- Minimal
		- Interface colors
            - Primary background
                - Dark: #242424
            - Secondary background
                - Dark: #1e1e1e
            - Border color
                - Dark: #4b4b4b
		- Code and syntax highlighting
			- Code background color
				- Dark: #181818
		- Headings
			- Level 1 Headings
				- H1 font size: 2em
				- H1 font weight: 700
                - H1 text color
                    - Dark: #8A8FB8
			- Level 2 Headings
				- H2 font size: 1.5
				- H2 font weight: 700
                - H2 text color
                    - Dark: #8AB8AF
				- H2 divider line: On
			- Level 3 Headings
				- H3 font size: 1.3em
                - H3 text color
                    - Dark: #8A8FB8
			- Level 4 Headings
				- H4 font size: 1.2em
				- H4 font variant: Normal
				- H4 font style: Italic
                - H4 text color
                    - Dark: #8AB8AF
			- Level 5 Headings
				- H5 font size: 1.1em
				- H5 font variant: Normal
				- H5 font style: Italic
                - H5 text color
                    - Dark: #8A8FB8
                - H5 divider line: On
			- Level 6 Headings
				- H6 font size: 1.1em
				- H6 font variant: Normal
				- H6 font style: Italic
                - H6 text color
                    - Dark: #8A8FB8
		- Text
            - Highlighted text background
                - Dark: #242424
			- Italic text color
				- Light: #6AA196
				- Dark: #8AB8AF
			- Bold text color
				- Light: #6A71A1
				- Dark: #8A8FB8
- "Tag Wrangler" by PJ Eby
- "Templater" by SilentVoid
	- Template folder location: Templates
    - Automatic jump to cursor: On
	- Remove and change the hotkey for "Templater: Open Insert Template Modal" to Ctrl+T
    - Template Hotkeys
        - Link to Current File: Alt+Shift+1
        - Insert Alias: Alt+Shift+2

## Fix heading shortcuts

1. Remove all "Shortcuts extender: Shortcut for symbol" that are bound to Alt as well as "Shortcuts extender: Shortcut for code fences (\`)"
2. Remove the defaults for "Go to tab#number" and change to Alt+number

## Graph View

- Filters
	- Tags: On
	- Existing files only: On
- Forces
	- Repel force: 12.50
