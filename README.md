# Vim and Neovim plugin configuration

- Keep track of which plugins I use, leveraging `git submodules`,
- Store and share snippets.

## Installation guide

Clone (including submodules) with :
```bash
git clone --recurse-submodules git@github.com:chataignault/vim.git ~/.vim
```

For Neovim, the configuration folder is rather `~/.config/nvim`,
so also run if both installed :
```bash
ln -s ~/.vim ~/.config/nvim
ln -s ~/.vimrc ~/.config/nvim/init.vim
```

## Cheatsheet

### Neovim
- `:checkhealth`
- `:echo &filetype`
- `:has("python3")`

**Try :**
- claude-code.nvim
- coc.nvim
- markdown-preview.nvim
- vim-prettier
- vscode-langserver

## References
- https://shapeshed.com/vim-packages/
- https://neovim.io/doc/user/provider.html
- https://stackoverflow.com/questions/3796927/how-do-i-git-clone-a-repo-including-its-submodules


