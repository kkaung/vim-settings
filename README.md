# vim-settings

Settings for vim that will make life a lot easier.

## Install

### Mac/Linux

Clone repo
```
git clone https://github.com/kkaung/vim-settings ~/.vim
```

### Windows

Navigate to profile in `cmd` (ex: `C:\users\myname`) and clone repo
```
> git clone https://github.com/kkaung/vim-settings vimfiles
```

Navigate to repo and update submodules
```
> cd vimfiles
> git submodule update --recursive --init
```

Copy `vimrc` and `gvimrc` to profile
```
> copy *vimrc ..
```

Prefix the names of the copied files in the profile with an underscore
```
> cd ..
> ren vimrc _vimrc
> ren gvimrc _gvimrc
```
