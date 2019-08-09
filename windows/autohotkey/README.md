# AutoHotkey

AutoHotkey script adapted from https://github.com/madslundt/keybindings

## Usage

1. Install AutoHotkey 1.1.* ([autohotkey.com/download/](https://www.autohotkey.com/download/) or `choco install autohotkey`).
2. Run the `.ahk` script.

Put the file (or a shortcut) to the Startup folder (Win + R, `shell:startup`) to run on startup.

You can remove the line `SetCapsLockState, AlwaysOff` to keep the normal `Caps Lock` behavior but it may cause inconvenience by activating when not intended.

## Known issues

It does not work in apps running as admin unless the script is also launched as admin (e.g. via the right click menu in File Explorer). You can use Task Scheduler to launch it as admin on startup.
