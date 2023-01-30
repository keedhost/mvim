## nvim
vim configuration

### Install:

For Linux:
```bash
rm -Rf ~/.config/nvim
git clone git clone git@github.com:keedhost/nvim.git ~/.config/nvim
git clone https://github.com/VundleVim/Vundle.vim.git ~/.config/nvim/bundle/Vundle.vim
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

nvim +'PlugInstall --sync' +qa
nvim +PluginInstall +qall
```
