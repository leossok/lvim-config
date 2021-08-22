# lvim-config
*lvim-config* is a personal config for LunarVim

## Install Neovim > v5.0
### Method 1 : Appimage
```
curl -o ~/nvim.appimage -L https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x ~/nvim.appimage
sudo ln -s ~/nvim.appimage /bin/nvim
```
### Method 2 : Extract tar
```
wget https://github.com/neovim/neovim/releases/download/v0.5.0/nvim-linux64.tar.gz
sudo tar -xzvf nvim-linux64.tar.gz -C /opt/
sudo ln -s /opt/nvim-linux64/bin/nvim /bin/nvim
```

## Install npm for LSP
```
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
```
