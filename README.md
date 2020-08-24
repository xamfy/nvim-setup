# neovim-setup
my neovim setup

### setup neovim on debian
```shell
# install neovim
sudo apt install neovim

# install vim-plug
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
 https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

# create a neovim config directory
mkdir ~/.config/nvim
```

### To install plugins using vim-plug
```
nvim +PlugInstall
```
