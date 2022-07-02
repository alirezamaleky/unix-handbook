# A handbook for Unix configuration

## Packages

```bash
brew install unar
brew install wget git gitui
brew install tmux htop neofetch
brew install vim
```

## Apps

```bash
brew install whatsapp telegram skype
brew install visual-studio-code
brew install google-chrome
brew install anydesk
brew install postman
```

### NodeJS

```bash
brew install nvm yarn
echo 'export NVM_DIR=~/.nvm' >> ~/.zshrc
echo 'source $(brew --prefix nvm)/nvm.sh' >> ~/.zshrc
nvm install --lts
npm i -g npm serve lerna typescript eslint prettier
```

## Config

```bash
sudo sysctl -w fs.inotify.max_user_instances=1024
sudo sysctl -w fs.inotify.max_user_watches=524288
```
