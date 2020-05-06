[![source.gif](https://media.giphy.com/media/11ISwbgCxEzMyY/source.gif)](https://github.com/waltercraig/mac-setup)

# Mac Setup
Some setup after a clean install.

## Apps to instal 
* [iA Writer](https://ia.net/writer)
* [Invision Studio](https://www.invisionapp.com/studio)
* [Google Chrome](https://www.google.co.uk/intl/en_uk/chrome/)
* [Firefox](https://www.mozilla.org/en-GB/firefox/new/)
* [MAMP](https://www.mamp.info/en/)
* [Hyper](https://hyper.is/)
* [vscode](https://code.visualstudio.com/)
* [Postman](https://www.postman.com/downloads/)
* [ImageOptim](https://imageoptim.com/)
* [Be Focused](https://xwavesoft.com/be-focused-pro-for-iphone-ipad-mac-os-x.html)
* [Codekit](https://codekitapp.com/)


## Customise Apps
### Terminal
* Install: https://draculatheme.com/terminal
* Activate
* Change font to IBM Plex mono - font size 18px

### Hyper
* Hack here: ~/Library/Application Support/Hyper/.hyper.js
* Install: https://hyper.is/plugins/hyperpower
* Install: https://hyper.is/plugins/hyperocean

### Visual Studio install 
Open from command line ⇧+⌘+P and type shell command then select Install 'code' command in PATH. Bingo

* Auto close tag - Jun Han
* Auto Rename tag - Jun Han
* Babel ES6/ES7 - dzannotti 
* ESLint - Dirk Beaumer
* GraphQL - Prisma
* Markdown All in One - You Zhang
* Path Intellisense - Christian Kohler
* Prettier - Esben Petersen
* Reactjs code snippets - charalampos Karypidis
* Snazzy Operator - Aaron Thomas
* vscode-icons - VSCode Icon Team
* vscode styled components - Julien Poissonier 
* Wordpress Snippets - wpdevtools.io

## Clean House (Some Mac customisations) 

### Remove Mac Screenshot Drop-Shadows

In Terminal / Hyper
```
defaults write com.apple.screencapture disable-shadow -bool true
```

Then
```
killall SystemUIServer
```

### Show Hidden Files

In Terminal / Hyper
```
defaults write com.apple.finder AppleShowAllFiles TRUE;killall Finder
```

### Install Homebrew 

In Terminal / Hyper
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install Node 
https://nodejs.org/en/

### Create Global .gitignore 
```
# Global file setup: https://gist.github.com/subfuzion/db7f57fff2fb6998a16c

# This file: https://github.com/github/gitignore/blob/master/Global/macOS.gitignore

# Exclude node modules 
node_modules

# General
.DS_Store
.AppleDouble
.LSOverride

# Icon must end with two \r
Icon

# Thumbnails
._*

# Files that might appear in the root of a volume
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk
```

## System Preferences 
Accessibility > Display > Cursor > Uncheck Shake mouse pointer to locate

Mouse > Secondary Click > Click on right side

## Fonts
* [IBM Plex](https://www.ibm.com/plex/)
* [Montserrat](https://fonts.google.com/specimen/Montserrat)
* [Open Sans](https://fonts.google.com/specimen/Open+Sans)
