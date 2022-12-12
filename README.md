# .ubuntu-home

## Ubuntu Config Files

### Usage

#### Clone This Repo
```
git clone https://github.com/Musa-Azeem/.ubuntu-home
```

#### Source config files
Add: 
- to .zshrc, `source ~/.ubuntu-home/.zshrc`
- to .vimrc, `source ~/.ubuntu-home/.vimrc`
- to .tmux.conf, `source-file ~/.ubuntu-home/.tmux.conf`

#### To export gnome color profile:

`dconf dump /org/gnome/terminal/legacy/profiles:/ > gnome-terminal-profiles.dconf`

To import gnome color profile:

`dconf load /org/gnome/terminal/legacy/profiles:/ < gnome-terminal-profiles.dconf`
