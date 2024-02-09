# nvim.init

## prerequisites

```bash
# iterm2
brew install iterm2

# fonts
brew install font-hack-nerd-font

# pyenv and pyenv-virtualenv
brew install pyenv pyenv-virtualenv

# list verions of python
pyenv install -l
# pick python version
pyenv install 3.11.7
# create neovim virtualenv
pyenv virtualenv 3.11.7 neovim
# activate and install neovim module
pyenv activate neovim
pip install neovim
pyenv deactivate
```

## install tmux

```bash
brew install tmux
mkdir -p ~/.config/tmux ~/.tmux/plugins
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
git clone git@github.com:tomroffe/tmux.init.git/ ~/.config/tmux
tmux source .config/tmux/tmux.conf
```

## install neovim

```bash
brew install neovim
mkdir -p ~/.config/.nvim/
git clone  git@github.com:tomroffe/nvim.init.git ~/.config/nvim
```
