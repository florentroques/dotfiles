# dotfiles (mac)

Notes for future TODO

## Use strap, an amazing script to bootstrap a minimal macOS development system.
https://github.com/MikeMcQuaid/strap

brew cask install google-chrome-dev
brew cask install phpstorm-eap #free phpstorm early access

### Install Mackup
brew install mackup

### Launch it and back up your files
mackup backup

### with Brewfile
brew tap homebrew/bundle
brew bundle

### change default shell interpreter to zsh
brew install zsh
chsh -s /bin/zsh

## install mac command line tools
xcode-select --install

## stop installing docs every time you install a gem
echo "gem: --no-document" >> ~/.gemrc


### Brewfile example
https://github.com/driesvints/dotfiles/blob/master/Brewfile

### Mac os preferences/settings
https://github.com/mathiasbynens/dotfiles/blob/master/.macos

### Fresh mac OS install TODO list
https://github.com/driesvints/dotfiles#a-fresh-macos-setup

### Check dotfiles tutorials and utilities
https://dotfiles.github.io/tutorials/

### Curated list of dotfiles resources
https://github.com/webpro/awesome-dotfiles

Great presentation on Homebrew and Mackup  
https://speakerdeck.com/anahkiasen/a-storm-homebrewin

Mackup more in details  
https://kevinjalbert.com/synchronizing-my-dotfiles/

### Handle brew services
brew cask install launchrocket

### check whalebrew for docker
https://github.com/whalebrew/whalebrew
