# Owlsayer Tmux Theme

A powerline-style tmux theme based on the Naysayer Emacs theme.

## Features

- **Session name on the left** with powerline styling
- **Window list** showing index and name
- **Prefix key indicator** - session name changes from cyan to red when prefix is pressed
- **No right-side clutter** - clean, minimal design

## Installation

### Using TPM (Recommended)

1. Add plugin to the list of TPM plugins in `~/.tmux.conf`:
   ```bash
   set -g @plugin 'owlfacegames/owlsayer-tmux'
   ```

2. Hit `prefix + I` to fetch and source the plugin.

### Manual Installation

1. Source the theme in your `~/.tmux.conf`:
   ```bash
   source-file /path/to/owlsayer-tmux.conf
   ```

2. Reload tmux configuration:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

