# srt-mode.vim
VIM mode script to debub .srt file timing (requires +float &amp; sox executable)

# Requirements

- vim with +float
- sox executable installed

# Install

```
    mkdir ~/.vim/plugins
    cp srtplay.vim ~/.vim/plugins/
```

# Usage

1. open .srt file in vim
1. move cursor to a block you are interested
1. press `gg` to listen block sound
1. press `gn` to move to next block
1. press `g;` to switch tempo among preset list
