# brewfile

## Finder setting
+ 隠しファイル表示
``` sh
defaults write com.apple.finder AppleShowAllFiles -boolean true
killall Finder
```

## exec command

``` sh
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew upgrade
brew install rcmdnk/file/brew-file

# install
brew file install
# update
brew file cask_upgrade -C
```
