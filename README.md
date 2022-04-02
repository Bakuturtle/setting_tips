# tmux
```bash
  set -g default-terminal 'screen-256color'
  set -g history-limit 1000
  
  set -g status-fg green
  set -g status-bg black
```


# vim
```bash

set hlsearch
set nu 
set autoindent
set autowrite
set autoread
set cindent 
set paste 
set showmatch
set smartcase
set smarttab
set smartindent

set history=256
set scrolloff=2
set shiftwidth=4
set softtabstop=4
set tabstop=4

```

# neovim
'''bash
    # tmux
```bash
  set -g default-terminal 'screen-256color'
  set -g history-limit 1000
  
  set -g status-fg green
  set -g status-bg black
```


# vim
```bash

set hlsearch
set nu 
set autoindent
set autowrite
set autoread
set cindent 
set paste 
set showmatch
set smartcase
set smarttab
set smartindent

set history=256
set scrolloff=2
set shiftwidth=4
set softtabstop=4
set tabstop=4

```

# neovim
'''bash
set showmatch               " show matching
set ignorecase              " case insensitive
set hlsearch                " highlight search
set incsearch

set tabstop=4               " number of columns occupied by a tab
set softtabstop=4           " see multiple spaces as tabstops so <BS> does the right thing
set expandtab               " converts tabs to white space
set shiftwidth=4            " width for autoindents
set smarttab
  
"indent
set autoindent              " indent a new line the same amount as the line just typed

"view
set number                  " add line numbers
set wildmode=longest,list   " get bash-like tab completions
"set cc=80                  " set an 80 column border for good coding style

"mouse setting
set mouse=a                 " enable mouse click
set mouse=v                 " middle-click paste with

"copy and paste
set clipboard=unnamedplus   " using system clipboard
 
  
set ttyfast                 " Speed up scrolling in Vim
syntax on                   " syntax highlighting
'''
'''
