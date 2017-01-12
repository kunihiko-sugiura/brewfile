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





# check
brew doctor

# install
brew file install
# update
brew file cask_upgrade -C
```


## sublime text
show console ctrl + ``

```
import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```


+ ConvertToUTF8
