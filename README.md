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

# Install Productivity Applications

brew install --cask google-backup-and-sync
brew install --cask google-chrome
brew install --cask kindle
brew install --cask spotify
brew install --cask adobe-acrobat-reader
brew install --cask shiftit
brew install --cask insominiax
brew install --cask evernote
brew install --cask viber


# Communication Tools

brew install --cask microsoft-teams
brew install --cask slack
brew install --cask zoomus
brew install --cask messenger

# Development Tools

brew install --cask dbeaver-ce
brew install --cask vscode
brew install --cask visual-studio
brew install --cask sublime-text
brew install --cask postman
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



