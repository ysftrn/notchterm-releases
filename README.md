# NotchTerm

A macOS terminal that lives in your notch. Hover over the notch 
area on your MacBook Pro to reveal a quick-access terminal — 
no keyboard shortcut needed, no Dock icon, just your mouse.

## Features
- Instant access — hover over the notch to show, move away to hide
- Full terminal emulation — any shell, any prompt, any config
- Nerd Font included — works with Powerlevel10k out of the box
- Shell session persists across show/hide cycles
- Drag to resize — size is remembered across launches
- Blur/vibrancy background
- Fully configurable via plain text config file
- Works across all Spaces and Mission Control
- Esc to hide from keyboard

## Requirements
- macOS 13.0 (Ventura) or later
- MacBook Pro with notch (2021 or later)

## Installation


[Download NotchTerm-0.1.2-beta.zip](https://github.com/ysftrn/notchterm-releases/releases/download/v0.1.2-beta/NotchTerm-0.1.2-beta.zip)

1. Unzip and drag NotchTerm.app to /Applications
2. Right-click → Open (not double-click) on first launch
3. Grant Accessibility permission when prompted

### Direct Download (from Releases)
Download the latest `.dmg` from the 
[releases page](https://github.com/ysftrn/notchterm-releases/releases).


## Getting Started
On first launch NotchTerm will ask for Accessibility permission. 
This is required to detect mouse movement over the notch area 
when other apps are in focus. NotchTerm does not read, record, 
or transmit any input data.

Once granted, hover your mouse over the notch to reveal the 
terminal.

## Configuration
NotchTerm is configured via a plain text file:
`~/.config/notchterm/notchterm.conf`

The file is created automatically on first launch with all 
options documented. Edit and save — changes are applied 
automatically.

### Available settings
| Setting | Default | Description |
|---|---|---|
| font-family | MesloLGS Nerd Font | Font name |
| font-size | 13 | Font size in points |
| theme | Default | Color scheme |
| opacity | 1.0 | Panel transparency |
| animation | fade | Show/hide animation |
| shell | $SHELL | Shell executable path |
| scrollback | 10000 | Scrollback buffer lines |
| width | 800 | Panel width in points |
| height | 400 | Panel height in points |
| cursor-style | block | block, underline, bar |
| cursor-blink | false | Blinking cursor |

## Credits
- [SwiftTerm](https://github.com/migueldeicaza/SwiftTerm) 
  by Miguel de Icaza — MIT License
- [MesloLGS Nerd Font](https://github.com/ryanoasis/nerd-fonts) 
  by Ryan L McIntyre — Apache License 2.0
- Catppuccin theme — MIT License
- Dracula theme — MIT License
- Solarized theme — MIT License
- One Dark theme — MIT License

## License
Copyright © 2026 Yusuf Torun. All rights reserved.
