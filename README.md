# Configurations
This repository contains all the configuration files for my development environtment setup
```sh
sudo apt update && sudo apt upgrade
```

## Oh My Zsh

```sh
sudo apt install curl
```

```sh
sudo apt install zsh
```

```sh
sudo chsh -s $(which zsh)
```

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

```sh
sudo git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```sh
sudo git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

Install the fonts from https://github.com/romkatv/powerlevel10k#fonts


copy the 
```sh 
wget -O ~/.zshrc https://raw.githubusercontent.com/Raveen2001/configs/main/.zshrc
```

```sh
wget -O ~/.p10k.zsh https://raw.githubusercontent.com/Raveen2001/configs/main/.zshrc
```


restart the terminal or type
```sh 
zsh
```

    
## tmux
```sh
sudo apt install tmux
```

```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

```sh
wget -O ~/.tmux.conf https://raw.githubusercontent.com/Raveen2001/configs/main/.tmux.conf
```

```sh
tmux new -s session
```
press ``` crtl + space ``` then ``` I ``` to install the plugins
press ``` crtl + space crtl + s ``` to save the session
press ``` crtl + space crtl + r ``` ro restore the session


## NVM
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
```


