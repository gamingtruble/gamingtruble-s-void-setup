### [Main branch](https://github.com/P-OEM/P-OEM-s-void-setup/tree/main)

## Skype setup
### this branch contains a simple guide for setting up skype in a xfce, void linux system

## [Skype introduction](#introduction)
## [Skype make launcher start from search](#make-launcher-start-from-search)
## [Skype turn of automated start](#turn-off-automated-start)

## Introduction
* skype is surprisingly simple to set up on void linux, you just install the `skype` package, create a launcher, and you should be good to go
* for this guide it's expected that the `skype` package is installed (you might need the `void-repo-nonfree` package to install the `skype` package)

## Make launcher start from search
* open launcher file with text editor
    * in terminal type `sudo TextEditorOfChoice /usr/share/applications/skypeforlinux.desktop`
        * change `Exec` line to `Exec=skypeforlinux %U`
        * add the line `Path=/usr/bin`
            * then save, log out and login, Done!

## Turn off automated start
* launch skype
    * log in
        * go to the tripple dot `...` menu up to the left, next to the bell icon
            * go to settings
                * then general
                    * then disable `Automatically start skype`
