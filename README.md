# Configurations
This repository contains all the configuration files for my development environtment setup
```sh
sudo apt update && sudo apt upgrade
```

## Oh My Zsh

```sh
sudo apt install zsh
sudo chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
sudo git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
sudo git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

Install the fonts from ``` https://github.com/romkatv/powerlevel10k#fonts ```
copy the ``` .zshrc ``` ``` .p10k.zsh ``` file now
restart the terminal or type ``` zsh ```



    
## tmux
```sh
sudo apt install tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
copy the ```.tmux.conf``` file

```sh
tmux new -s session
```
press ``` crtl + space ``` then ``` I ``` to install the plugins
press ``` crtl + space crtl + s ``` to save the session
press ``` crtl + space crtl + r ``` ro restore the session
