# tmux config file
Here is a tmux config file forked from Drams of Code, the tutorial video linked [here](https://www.youtube.com/watch?v=DzNmUNvnB04).

## Install
First, clone this repo by:
```bash
git clone https://github.com/yfrua/tmux.git ~/.config
```

And install `tpm` to get access to plugins, by
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

After that, load it to tmux by
```bash
tmux source ~/.config/tmux/tmux.conf
```

Finally, run `tmux` and press `Prefix + I` (`Ctrl+Space + I`) to install the plugins.

## Usage
The prefix key is changed to `Ctrl+space` rather than `Ctrl+b`.

By setting up `vim-tmux-navigator`, you can use `Ctrl+h/j/k/l` like vim shortcuts to navigate between tmux panes or between vim pane and tmux pane.

### Common shortcuts
- `Prefix + h/j/k/l`: move to left/down/up/right pane
- `Alt + ←/→/↑/↓`: move panes directly without prefix
- `Shift + ←/→`: switch to previous/next window
- `Alt + Shift + h/l`: switch to previous/next window
- `Prefix + "`: split pane vertically (top/bottom)
- `Prefix + %`: split pane horizontally (left/right)

### Copy mode (vim style)
This config enables `vi` mode for copy mode.
- `Prefix + [`: enter copy mode
- `v`: begin selection
- `Ctrl+v`: toggle rectangle selection
- `y`: copy selection and exit copy mode (with `tmux-yank`)

### Notes
- Window and pane indexes start from `1`.
- Windows are renumbered automatically after closing.
- Mouse mode is enabled.
