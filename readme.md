## How to setup a new laptop?

1. [Homebrew](http://brew.sh/index.html)
    - install wget
2. Xcode, dropbox, atom, chrome
3. iTerm -> Zsh -> Oh my Zsh
4. vi -> [spf13](https://github.com/spf13/spf13-vim)
5. tmux (In order to work with zsh and mac os, you also need to install [library](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard/))
6. [mackup](https://github.com/lra/mackup)
    - Copy mackup.cfg file from dropbox into home directory
    - mackup restore
    - vi -> PluginInstall
7. Clone [dot_file](https://github.com/elmoonwy/dotfile)
    - copy `.vimrc.local` into home directory
    - vi -> PluginInstall
8. Setup Git
    - git config --global core.editor /usr/bin/vim
