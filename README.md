# Rubber themes
A collection of color schemes with minimal amount of highlighting for Vim. Based on [rubber-theme](https://github.com/apust/vscode-rubber-theme) for VSCode. .

Inspired by the same premise of the [alabaster color scheme](https://github.com/tonsky/sublime-scheme-alabaster) for Sublime Text it defines just four classes:
- Strings
- Known constants (numbers, symbols, booleans)
- Comments
- Functions

## Getting Started

### Available themes
- rubber
- rubber-owl

### Installation

**Using** [vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'VonHeikemen/rubber-themes.vim'
```

### Activation
```vim
" For vim > 8
if (has("termguicolors"))
 set termguicolors
endif

" For Neovim 0.1.3 and 0.1.4
let $NVIM_TUI_ENABLE_TRUE_COLOR=1

syntax enable
colorscheme rubber
```
