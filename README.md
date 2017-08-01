My neovim setup. Plugins are managed by Plug and include:

- Deoplete - tab completion
- Airline - status/tab line
- Oceanic - themeing
- FZF - fuzzy search
- Ale - linting

### install
```
mkdir -p ~/.config/nvim &&\
git clone https://github.com/peterjcaulfield/nvim ~/.config/nvim &&\
cd ~/.config/nvim && ./install.sh &&\
nvim +PlugClean +PlugInstall +qa
```
