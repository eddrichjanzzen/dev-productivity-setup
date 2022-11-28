# dev-productivity-setup

Set up for development environment for Mac OS

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## In your Desktop: create a file called `install.sh`

```
$ cd Desktop
$ touch install.sh
```

### Copy the following code into `install.sh`

```
#!/bin/bash

# Install Productivity Applications

brew install google-drive
brew install google-chrome
brew install kindle
brew install spotify
brew install adobe-acrobat-reader
brew install shiftit
brew install evernote
brew install brave-browser
brew install iterm2

# Communication Tools

brew install microsoft-teams
brew install slack
brew install zoomus
brew install messenger
brew install telegram
brew install viber
brew install discord
brew install ticktick


# Development Tools

brew install dbeaver-community
brew install visual-studio-code
brew install sublime-text
brew install postman
brew install docker

# Command Line Tools

brew install git
brew install terraform
brew install aws-cli
brew install azure-cli
brew install nvm


# Programming Languages and Frameworks

brew install python
brew install java
brew install node

```

## run `install.sh`

```
$ cd Desktop
$ sh install.sh
```
