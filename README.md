# Tmux Configuration

This repository contains my custom tmux configuration file (`.tmux.conf`). It includes various customizations to improve tmux usability, such as:
- Better navigation between panes
- Keybindings for pane resizing and switching
- Plugins to manage tmux sessions and enhance its functionality (using [tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect) and [tmux-continuum](https://github.com/tmux-plugins/tmux-continuum))
- Custom status bar themes using [catppuccin/tmux](https://github.com/catppuccin/tmux)

## Features

- **Improved Pane Navigation**: Use `h`, `j`, `k`, `l` to switch between panes, similar to Vim keybindings.
- **Resizing Panes**: Use `Alt + h/j/k/l` to resize panes.
- **Session Management**: Automatically save and restore tmux sessions with `tmux-resurrect` and `tmux-continuum`.
- **Custom Status Bar**: Beautifully styled status bar with session info and IP address using the [catppuccin theme](https://github.com/catppuccin).
  
## Installation

```bash
wget -P ~ https://github.com/a0ffis/tmux-config/raw/main/.tmux.conf
