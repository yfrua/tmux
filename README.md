# tmux config file
Here is a tmux config file forked from Drams of Code, the tutorial video linked [here](https://www.youtube.com/watch?v=DzNmUNvnB04).

## Install
You need to install `tpm` first to get access to plugins, by command
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

After that, load it to tmux by
```bash
tmux source ~/.config/tmux/tmux.conf
```

Finally, run `tmux` and press `Ctrl+b + I` to install the plguins.

## Usage
The prefix key is changed to `Ctrl+space` rather than `Ctrl+b`.

By setting up `vim-tmux-navigator`, you can use `Ctrl+h/j/k/l` like vim shortcuts to navigate between tmux panes or between vim pane and tmux pane.


