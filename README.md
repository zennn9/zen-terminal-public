# zen-terminal

`zen-terminal` is a desktop command launcher built with Tauri and React.

It is designed around fast keyboard-first use: open the app, type a short command, and do something immediately.

## What It Does

- Launch apps and saved shortcuts
- Run quick terminal-style commands
- Search the web and media sites
- Control YouTube Music
- Use AI and JP translation commands
- Customize startup and terminal behavior through config

## Example Commands

```text
help
config
alias
launch
music
timer
tc
ai
jp hello
update
version
```

## Features

- Minimal terminal-style interface
- Global shortcut support
- Config system with special UI-based settings
- Background image customization
- Built-in updater for packaged releases

## Updates

This repository is used to publish public release files for the app.

The app checks:

```text
https://github.com/zennn9/zen-terminal-public/releases/latest/download/latest.json
```

If a newer version exists, `zen-terminal` can install it through the built-in updater.

## Install

Download the latest Windows `.msi` release from the Releases page and install it normally.

## Notes

- This is the public release repository.
- It does not contain the full application source.
