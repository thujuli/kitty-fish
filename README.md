# kitty-fish
Configuration for Kitty and Fish for daily driver
## Install Kitty Terminal
`sudo apt install kitty`
## Keyboard Shortcuts for Kitty
> [Ubuntu](https://help.ubuntu.com/stable/ubuntu-help/keyboard-shortcuts-set.html.en)
`<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>t</kbd>`
## Install Fish Shell
- `sudo apt-add-repository ppa:fish-shell/release-3`
- `sudo apt update`
- `sudo apt install fish`
## Setup Fish for default shell
- `echo /usr/local/bin/fish | sudo tee -a /etc/shells`
- `chsh -s /usr/bin/fish` 
