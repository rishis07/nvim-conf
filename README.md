# Eric is learning nvim
here I am storing all my confs for nvim. I have no idea what I am doing.

## Guia de donde saque todo
https://www.youtube.com/playlist?list=PLhoH5vyxr6QqPtKMp03pcJd_Vg8FZ0rtg

## Install NeoVim
- Mac
```
brew install neovim
```

Copy this repo into ~/.config/nvim

## Install py support
pip3 install pynvim

## Install node
you need node dude

## install yarn
npm i -g yarn
## Check Plugin Status
```
:PlugStatus
```

## Install plugins
```
brew install fzf

brew install ripgrep

brew install --HEAD universal-ctags/universal-ctags/universal-ctags

brew install the_silver_searcher

brew install fd
```


```
:PlugInstall
```

## Coc install
Cocinstall coc-json coc-python coc-snippets coc-vimlsp coc-tsserver coc-explorer

## FZF cheatsheet
:FZF normal FZF
:Files search files
:Rg fzf for files and inside files
:BLines sarch in buffer
:Lines search all buffers
:Buffers search buffers

## Some movements I need to learn
f [char]: looks for that char 
t [char]: looks for that char (left)
    , : move next char aleft
    ; : move next char right 

I: insert mode at the begining of the line
A: insert mode at the end of the line

{: up a paragrah
}: down a paragrah

ctr d: half page down
ctr u: half page up 

G: all the way down
gg: all the way up
:number: go to specific line

/[char]: sarch down
?[char]: sarch up
*: sarch for the word on the cursor
#: inverted search

shift k: def of function
