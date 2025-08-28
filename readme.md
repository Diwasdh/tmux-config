# tmux-config

My personal tmux configuration with a clean status bar, mouse support, and productivity-focused tweaks.

## Features

- **Quick reload**: `prefix + r` (reloads `~/.config/tmux/tmux.conf`)
- **Status bar**:
  - Positioned at the **top**
  - Left: **username**
  - Middle: **windows list** (current window highlighted)
  - Right: **current time (HH:MM)**
- **Mouse support**: pane/window selection, resizing, and scrolling
- **Indexing**:
  - Windows start at `1`
  - Panes start at `1`
  - Windows renumber automatically
- **Colors**:
  - Background: `#303446`
  - Foreground: `#c6d0f5`
  - Current window: `#8caaee`
  - Username (left): `#f5bde6`
  - Time (right): `#f2cdcd`

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Diwasdh/tmux-config.git ~/.tmux-config

   
2. Backup existing tmux config (if any):

    ```bash
    mv ~/.tmux.conf ~/.tmux.conf.backup


3. Symlink the config:
    
    ```bash 
    ln -s ~/.tmux-config/.tmux.conf ~/.tmux.conf


or copy it directly:

    ```bash
    cp ~/.tmux-config/.tmux.conf ~/


4. Reload tmux (if running):

    ```bash 
    tmux source-file ~/.tmux.conf


Or restart tmux to apply changes.


