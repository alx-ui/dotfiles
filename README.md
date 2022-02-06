# Meus dotfiles

## 👨🏾‍💻 Instalação

```sh
### Oh My ZSH
sudo sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/lukechilds/zsh-nvm ~/.oh-my-zsh/custom/plugins/zsh-nvm 
rm -rf ~/.zshrc

### Setup dos dotfiles
git clone https://github.com/ialexanderbrito/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
ln -s ~/.dotfiles/.hyper.js ~/.hyper.js

## How to extract current installed files?
```sh
cd ~/.dotfiles && git add . && git commit -m "update" && git push 
```
