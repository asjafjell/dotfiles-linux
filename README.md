# Dotsettings (med noko attåt)

## Installer apper
```
brew install zsh oh-my-zsh
brew cask install sublime-text2 spotify spectacle sourcetree
```

## Andre dotsettings som er interessante
1. [nicsp](https://github.com/nicksp/dotfiles/blob/master/osx/set-defaults.sh) (se script for å sette opp MacOS-spesifikke ting)
1. Forøvrig alle de andre på [Github](https://dotfiles.github.io/)

## Kommandoer som bør kjøres 
Vurder å lag en egen fil for dette etterhvert

```
#Make sure tags are pushed by default in Git
git config --global push.followTags true

#Symlink Zsh config file to dotfiles repo
ln -s ~/.dotfiles/zsh/.zshrc ~/.zshrc

#Symlink SSH config to dotfiles repo
ln -s ~/.dotfiles/ssh/config ~/.ssh/config

#Add 'subl' as a command for running sublime from Terminal. More info here:https://gist.github.com/olivierlacan/1195304
ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/sublime
```
