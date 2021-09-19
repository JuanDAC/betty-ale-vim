# betty-ale-vim
> An extention for Ale which integrate Betty's linter of holberton school
with vim

## How to install

### Prerequisites

* This is an extension of [ALE], So you need to install it first

### Installation with Vim-Plug

* List the plug with the `Plug` command<br>
`Plug 'JuanDAC/betty-ale-vim'`


* Include the betty-style and betty-doc into the ale linters<br>
`let g:ale_linters = {'c': ['betty-style', 'betty-doc']`}

#### Example

```vim
"Call Vim-plug
call plug#begin('~/.vim/plugged')
	Plug 'dense-analysis/ale'|          "ALE is a prerequisite
	Plug 'JuanDAC/betty-ale-vim'|       "Program
call plug#end()


let g:ale_linters = {'c':['betty-style', 'betty-doc', 'gcc']}
```

### Check it in action
![vim-ale-demo](https://media.giphy.com/media/izojA1Gn2C7rjKbdGE/giphy.gif)

## Author
[JuanDAC](https://github.com/JuanDAC)
[Athesto](https://github.com/Athesto)

## Support us
This is single project that we to with love, and If your like it please give us an star ⭐ and share it with your peers

<!--links-->
[ALE]: https://github.com/dense-analysis/ale
