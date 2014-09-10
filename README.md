dotvim
======
My cross-platform .vimrc

# Prerequisites
- Git, check that is in your `$PATH` (or `%PATH%` in Windows)
- Python, check that is in your `$PATH` (or `%PATH%` in Windows)
  - For Windows use [python x64](https://www.python.org/download)
- Lua, check that is in your `$PATH` (or `%PATH%` in Windows)
  - For Windows use [lua x64](http://joedf.users.sourceforge.net/luabuilds/)
    - You can copy the DLL to your VIM binaries folder
- [Ag](https://github.com/ggreer/the_silver_searcher)
  - For Windows you can easily install using [Chocolatey](http://chocolatey.org/)

## Vim 7.4+ compiled with python/ruby/lua

### Mac
- `brew install macvim --with-cscope --with-lua --HEAD`
    - Use `macvim -v` for terminal vim

### Ubuntu
- Compile from scratch following this [guide](http://zaiste.net/2013/05/compiling_vim_with_ruby_and_python_support_on_ubuntu/)

### Windows
- Use the latest compiled version from [here](http://solar-blogg.blogspot.ca/p/vim-build.html)
    - In that page you have instructions if you want to compile using Visual Studio
- You can use terminal vim in Windows if you want, I recommend using a console
  emulator:
    - [cmder](http://bliker.github.io/cmder/)

# Installation
- Copy or symlink .vimrc to your $HOME (or `%HOMEPATH%` in Windows)
- Run vim, if it doesn't detect vundle package manager, it will install it with
  all the plugins in $HOME/.vim (or `%HOMEPATH%\.vim` in Windows)

# Credits
- https://github.com/fisadev/fisa-vim-config
- https://github.com/garybernhardt/dotfiles
- https://bitbucket.org/sjl/dotfiles/src
- https://github.com/spf13/spf13-vim

