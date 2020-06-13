# btw-st
My build of Simple (Suckless) Terminal

## Patches

- Font2 - Allows usage of 2+ fonts with st, used here for emoji and Font Awesome support   
Please make sure that `ttf-hack` `ttf-joypixels` `ttf-font-awesome` and `awesome-terminal-fonts` are installed or change the fonts yourself
- Gruvbox Dark - Color scheme
- Scrollback - Adds scrolling support with `Shift+MsWheel` or `Alt+J/K`
- w3m - Fixes w3m image previews in st
    
##### The bindings are default aside from the ones listed above

## Help/FAQ

- What version of st is this?       
This build is currently on version 0.8.3, the current latest

- st crashes when it sees and emoji!        
You must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR. If you don't st will crash when rendering emojis. If it's still crashing try to install [lib32-libxft-bgra](https://aur.archlinux.org/packages/lib32-libxft-bgra/). Hopefully in the future `libxft-bgra` will be added to the official release and will no longer be needed.
