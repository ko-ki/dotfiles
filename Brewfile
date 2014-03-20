# export HOMEBREW_CASK_OPTS="--appdir=/Applications --caskroom=/usr/local/Caskroom"

# Make sure using latest Homebrew
update

# Update already-installed formula
upgrade

# Add Repository
tap phinze/homebrew-cask || true
tap ko-ki/homebrew-mycask || true
tap homebrew/binary || true

# Packages for development
install zsh
install git
install vim
install curl
install wget
install tree
install imagemagick
install ghostscript
install node
install libtool
install openssl
install sl
install watch
install phantomjs
install cmake

# Packages for brew-cask
install brew-cask

# .dmg from brew-cask
cask install google-chrome
cask install virtualbox
cask install vagrant
cask install adobe-creative-cloud
cask install alfred
cask install appcleaner
cask install arduino
cask install bartender
cask install bettertouchtool
cask install blender
cask install codekit
cask install xscope
cask install sourcetree
cask install sublime-text
cask install totalfinder
cask install totalterminal
cask install istat-menus
cask install keyremap4macbook
cask install skype
cask install vlc
cask install mou
cask install dropbox
cask install sophos-anti-virus-home-edition
cask install hyperswitch
# ko-ki/homebrew-mycask
cask install totalspaces2

cask alfred link

# Remove outdated versions
cleanup
