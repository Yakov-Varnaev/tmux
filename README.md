
- Linux/MacOS installation

```
git clone https://github.com/Yakov-Varnaev/tmux.git "${XDG_CONFIG_HOME:-$HOME/.config}"
```

- Windows

Just google: "How to install Linux?"

## First run

After you've cloned the repo. Install all the dependencies:

https://github.com/catppuccin/tmux - follow the docs

```<prefix> + I```



# How to reset tmux

1. Move or rename tmux.conf file
2. execute `tmux kill-server` 
3. bring tmux.conf file back
4. run tmux + `tmux ~/.config/tmux/tmux.conf` then `<prefix> + I`
