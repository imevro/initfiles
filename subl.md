## Sync with Dropbox
##### Initial setup
    mkdir Dropbox/Sublime\ Text\ 2
    
    cp -r ~/Library/Application\ Support/Sublime\ Text\ 2/Installed\ Packages ~/Dropbox/Sublime\ Text\ 2
    cp -r ~/Library/Application\ Support/Sublime\ Text\ 2/Packages ~/Dropbox/Sublime\ Text\ 2
    cp -r ~/Library/Application\ Support/Sublime\ Text\ 2/Pristine\ Packages ~/Dropbox/Sublime\ Text\ 2

    ln -s ~/Dropbox/Sublime\ Text\ 2/Installed\ Packages ~/Library/Application\ Support/Sublime\ Text\ 2/Installed\ Packages
    ln -s ~/Dropbox/Sublime\ Text\ 2/Packages ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    ln -s ~/Dropbox/Sublime\ Text\ 2/Pristine\ Packages ~/Library/Application\ Support/Sublime\ Text\ 2/Pristine\ Packages

##### Run sync

    rm -rf ~/Library/Application\ Support/Sublime\ Text\ 2/Installed\ Packages
    rm -rf ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    rm -rf ~/Library/Application\ Support/Sublime\ Text\ 2/Pristine\ Packages

    ln -s ~/Dropbox/Sublime\ Text\ 2/Installed\ Packages ~/Library/Application\ Support/Sublime\ Text\ 2/Installed\ Packages
    ln -s ~/Dropbox/Sublime\ Text\ 2/Packages ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    ln -s ~/Dropbox/Sublime\ Text\ 2/Pristine\ Packages ~/Library/Application\ Support/Sublime\ Text\ 2/Pristine\ Packages

## `subl` command

    ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl