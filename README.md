dotfiles
========

dotfiles

# Install via shell

## Install from brewfile
brew install $(cat Brewfile|grep -v "#")

## Install from caskfile
brew cask install $(cat Caskfile|grep -v "#")
