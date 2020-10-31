# newdotfiles
Linux configuration files

## Install
Using [simplesetup](https://github.com/noahjutz/simplesetup):
```
curl https://raw.githubusercontent.com/noahjutz/simplesetup/v1.0.0/simplesetup.sh | bash
```
Custom:
```
git clone --bare https://github.com/noahjutz/dotfiles $HOME/.cfg
git --git-dir=$HOME/.cfg/ --work-tree=$HOME checkout -f
```

## Edit
Use the `config` alias. To show git status excluding untracked files:
```
config status -u no
```
