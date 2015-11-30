NutBunnies Crazy Overdone VIM
=============================
Notes:
* This configuration has only been used on Linux, FreeBSD and OSX (MacVim).  I believe it will work on Windows but IDK.
* Several of the plugins require VIM to be compiled with Ruby support

Install
-------
    cd ~
    git clone git://github.com/nutbunnies/vimhome.git .vim
    ln -s ~/.vim/vimrc ~/.vimrc
    cd ~/.vim
    git clone https://github.com/gmarik/vundle.git bundle/vundle
    vim +BundleInstall +qall
