# Tmux

#### Install tmux
On Arch Linux
```
sudo pacman -S tmux
```

On Ubuntu
```
sudo apt install tmux
```

#### Clone TPM: (Tmux Plugin Manager)
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

#### Install all plugins
Enter a tmux session
Press prefix + I (capital i, as in Install) to fetch the plugin.


#### Reload TMUX environment so TPM is sourced:
```
# type this in terminal if tmux is already running
tmux source ~/.config/tmux/tmux.conf
```

### CLI

Attach to tmux session
```sh
tmux a
````

### Main bindings

Prefix + d to detach from session
Prefix + s to switch between sessions
