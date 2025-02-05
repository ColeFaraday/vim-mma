# vim-mma

**This fork**: In my neovim there was a bug that the omnicompletion only worked for a few Mathematica functions. It appears that this is because the list was in someway overloaded on mmaSystemSymbol. I simply divided all of the functions into more syntax groups (mmaSystemSymbol1,..., mmaSystemSymbol14).

A Vim/Neovim plugin to provide [Wolfram Mathematica](https://wolfram.com/language/) language support.

This is a fork of [vim-mathematica](https://github.com/rsmenon/vim-mathematica) with some improvements.

![](https://user-images.githubusercontent.com/20282795/51797239-b7e20000-223a-11e9-8a06-aec35baaa01a.png)

### Installation

Preferred plugin manager is [vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'voldikss/vim-mma'
```

### Credits

- @[rsmenon](https://github.com/rsmenon)

- @[arnoudbuzing](https://github.com/arnoudbuzing)
