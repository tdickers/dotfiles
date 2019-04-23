# Dotfiles

Basic layout. Clone to `$HOME/.dotfiles`. Symlink the following to `$HOME`:
* `.zshrc`

Then, create `$HOME/.dotfiles/.local_settings` and include any private or machine-specific info.

## Plugins
Some user plugins need to be installed added to .local_settings:
* https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md
* https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md 

## TODO
Look into `$ZDOTDIR` and `.zshenv`.
Plugin list should gracefully degrade.
