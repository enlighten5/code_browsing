# terminal config  
`sudo apt-get install zsh`  
`sudo apt-get install terminator`    
`chsh -s /bin/zsh`    
`log out and log in`    
`wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh`  
`cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc`  
`source ~/.zshrc`
## zsh theme  
`ys`
## zsh-autosuggestions
`git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions`  
`add plugin in .zshrc`
## Terminator Font  
DejaVu Sans Mono Book 12
## Build-in color  
Solarized Dark and Tango  

## Terminator Theme  
`git clone https://github.com/ghuntley/terminator-solarized.git`  
`cd terminator-solarized`   
`mkdir -p ~/.config/terminator/`  
`touch ~/.config/terminator/config`  
`cp config ~/.config/terminator`

# vim_config
## Configuration
`sudo apt-get install cscope`  

`sudo apt-get install ctags`  

`cscope -R -b -q`  

`ctags -R *`  

`~/.bashrc: CSCOPE_DB=/<path_to_source_code>/cscope.out; export CSCOPE_DB`  
`~/.vimrc: source ~/.vim/autoload/cscope_maps.vim`  
## Instructions
`ctrl + ]` to jump into the function  
`ctrl + t` to jump back  
`:tabe filename` to open a file in vim table  

