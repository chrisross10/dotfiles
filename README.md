# dotfiles

This repository contains a configuration file `.vimrc` for my **vim** settings and various plugins.

### vim packages

* [Vundle](https://github.com/VundleVim/Vundle.vim) (vim plugin manager)
* [Ctrl-p](https://github.com/ctrlpvim/ctrlp.vim) (full path fuzzy file finder)
* [JsHint](https://github.com/wookiehangover/jshint.vim) (spots errors and common mistakes in JavaScript code)
* [SuperTab](https://github.com/ervandew/supertab.git) (allows you to use <Tab> for all your insert completion needs)
* [Sytastic](https://github.com/scrooloose/syntastic.git) (syntax checking hacks for vim)
* [The NERD Tree](https://github.com/scrooloose/nerdtree) (allows you to explore your filesystem and to open files and directories)

### Installation instructions
* Copy and move .vimrc into ~ directory
```
git clone https://github.com/chrisross10/dotfiles.git /dotfiles
cp /dotfiles/.vimrc ~/.vimrc
rm -rf /dotfiles

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
git clone https://github.com/kien/ctrlp.vim.git ~/.vim/bundle/ctrlp.vim
git clone https://github.com/wookiehangover/jshint.vim.git ~/.vim/bundle/jshint.vim
git clone https://github.com/ervandew/supertab.git ~/.vim/bundle/SuperTab
git clone https://github.com/scrooloose/syntastic.git ~/.vim/bundle/Syntastic
git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/The-NERD-tree
```
