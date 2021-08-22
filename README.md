# lvim-config
**lvim-config** is a personal config for LunarVim

## Requirements
### 1. Install Neovim > v5.0
#### Method A : Appimage
```
curl -o ~/nvim.appimage -L https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x ~/nvim.appimage
sudo ln -s ~/nvim.appimage /bin/nvim
```
#### Method B : Extract tar
```
wget https://github.com/neovim/neovim/releases/download/v0.5.0/nvim-linux64.tar.gz
sudo tar -xzvf nvim-linux64.tar.gz -C /opt/
sudo ln -s /opt/nvim-linux64/bin/nvim /bin/nvim
```

### 2. Install LunarVim
repo: https://github.com/LunarVim/LunarVim
**One Command Install**
```
bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/master/utils/installer/install.sh)
```


### 3. Install nodejs &  npm for LSP
```
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
```

## Install config
```
curl -o ~/.config/lvim/config.lua -L https://raw.githubusercontent.com/ohsirawat/lvim-config/master/config.lua
```
