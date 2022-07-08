# A handbook for Unix configuration

## Packages

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
brew install unar
brew install wget git gitui
brew install tmux htop
brew install neofetch stats
brew install vim
```

## Apps

```bash
brew install whatsapp skype
brew install visual-studio-code
brew install google-chrome firefox
brew install anydesk
brew install kap
brew install postman
```

### NodeJS

```bash
brew install nvm yarn
echo 'export NVM_DIR=~/.nvm' >> ~/.zshrc
echo 'source $(brew --prefix nvm)/nvm.sh' >> ~/.zshrc
nvm install --lts
npm i -g npm serve lerna yalc typescript eslint prettier jest
```

## Config

```bash
sudo sysctl -w fs.inotify.max_user_instances=1024
sudo sysctl -w fs.inotify.max_user_watches=524288
```
