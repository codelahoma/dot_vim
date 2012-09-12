# The Vim Configuration of Codelahoma (blatantly forked from mutewinter/dot\_vim)

[See dot_vim's Stats on GitEgo](http://gitego.com/codelahoma/dot_vim)

## Installation

1. `git clone http://github.com/codelahoma/dot_vim.git` in your home folder.
2. `mv dot_vim .vim`
3. `cd .vim`
4. `rake vim:link` to make the .vimrc symbolic link.
5. Install [Vundle](https://github.com/gmarik/vundle) with `git clone http://github.com/gmarik/vundle.git bundle/vundle`
6. Run Vim and type `:BundleInstall` to install the plugins with Vundle.
7. Enjoy enhanced productivity, increased levitation, reduced watermelon-related accidents, and startling sex appeal.

## Screenshots

**MacVim** / **Windows gVim**

[![MacVim](https://github.com/codelahoma/dot_vim/raw/master/screenshots/MacVim1_small.png)](https://github.com/codelahoma/dot_vim/raw/master/screenshots/MacVim1.png) [![Windows gVim](https://github.com/codelahoma/dot_vim/raw/master/screenshots/Windows1_small.png)](https://github.com/codelahoma/dot_vim/raw/master/screenshots/Windows1.png)

## Requirements

**Mac**

 * [MacVim](https://github.com/b4winckler/macvim) - I'm currently using [snapshot 64](https://github.com/b4winckler/macvim/downloads)

**Windows**

 * [gVim](http://www.vim.org/download.php#pc) - I'm currently using [Wu Yongwei's](http://wyw.dcweb.cn) pre-compiled [gVim 7.3.333](http://wyw.dcweb.cn/download.asp?path=vim&file=gvim73.zip) because it has Ruby support and the latest patches

## Notes

Be sure to always edit the vimrc using `,v`, which opens the vimrc in the .vim folder. Vim has a nasty habit of overriding symlinks.

## Plugin Installation / Requirements

I may make this more verbose later, but for now, here's a list of plugins that require further installation:

 * [Command-T](https://github.com/wincent/Command-T) Needs compilation.
 * [Fugitive](https://github.com/tpope/vim-fugitive) Requires Git to be installed.
 * [syntastic](https://github.com/scrooloose/syntastic) Requires many different binaries installed depending on what filetypes you want it to check.
 * [ack.vim](https://github.com/mileszs/ack.vim) Requires [ack](http://betterthangrep.com/) to be installed.
 * [Menlo for Powerline](https://gist.github.com/1627888) The custom font I'm using for vim-powerline.

## Plugin List

_Note: Auto generated by `rake plugins:update_readme`_


 * [vim-easymotion](https://github.com/Lokaltog/vim-easymotion) - Vim motions on speed!
 * [ultisnips](https://github.com/SirVer/ultisnips) - Official Mirror of UltiSnips trunk on LaunchPad. Send pull requests to SirVer/ultisnips!
 * [vundle](https://github.com/gmarik/vundle) - Vundle, the plug-in manager for Vim
 * [tagbar](https://github.com/majutsushi/tagbar) - Vim plugin that displays tags in a window, ordered by class etc.
 * [gist-vim](https://github.com/mattn/gist-vim) - vimscript for gist
 * [zencoding-vim](https://github.com/mattn/zencoding-vim) - zen-coding for vim: http://code.google.com/p/zen-coding/
 * [jellybeans.vim](https://github.com/nanotech/jellybeans.vim) - A colorful, dark color scheme for Vim.
 * [sbd.vim](https://github.com/orftz/sbd.vim) - Close buffers smartly.
 * [itchy.vim](https://github.com/programble/itchy.vim) - Scratch buffers for Vim
 * [golden-ratio](https://github.com/roman/golden-ratio) - Automatic resizing of Vim windows to the golden ratio 
 * [nerdtree](https://github.com/scrooloose/nerdtree) - A tree explorer plugin for vim.
 * [gundo.vim](https://github.com/sjl/gundo.vim) - A git mirror of gundo.vim
 * [vim-abolish](https://github.com/tpope/vim-abolish) - abolish.vim: easily search for, substitute, and abbreviate multiple variants of a word
 * [vim-commentary](https://github.com/tpope/vim-commentary) - commentary.vim: comment stuff out
 * [vim-endwise](https://github.com/tpope/vim-endwise) - endwise.vim: wisely add "end" in ruby, endfunction/endif/more in vim script, etc
 * [vim-fugitive](https://github.com/tpope/vim-fugitive) - fugitive.vim: a Git wrapper so awesome, it should be illegal
 * [vim-repeat](https://github.com/tpope/vim-repeat) - repeat.vim: enable repeating supported plugin maps with "."
 * [vim-surround](https://github.com/tpope/vim-surround) - surround.vim: quoting/parenthesizing made simple
 * [vim-unimpaired](https://github.com/tpope/vim-unimpaired) - unimpaired.vim: pairs of handy bracket mappings
 * [vim-session](https://github.com/xolox/vim-session) - Extended session management for Vim (:mksession on steroids)
 * [VimOrganizer](https://github.com/hsitz/VimOrganizer) - VimOrganizer is partly a clone of Emacs' Org-mode, and partly a front end to Org-mode itself.  Do Org in Vim.
 * [vim-haml](https://github.com/tpope/vim-haml) - Vim runtime files for Haml, Sass, and SCSS
 * [vim-rails](https://github.com/tpope/vim-rails) - rails.vim: Ruby on Rails power tools
 * [vim-rake](https://github.com/tpope/vim-rake) - rake.vim: it's like rails.vim without the rails
 * [vim-rvm](https://github.com/tpope/vim-rvm) - rvm.vim: switch Ruby versions from inside Vim
 * [vim-ruby](https://github.com/vim-ruby/vim-ruby) - Vim/Ruby Configuration Files
 * [EasyMotion](https://github.com/vim-scripts/EasyMotion) - Vim motions on speed!
 * [ZoomWin](https://github.com/vim-scripts/ZoomWin) - Zoom in/out  of windows (toggle between one window and multi-window)
 * [ctrlp.vim](https://github.com/vim-scripts/ctrlp.vim) - Fuzzy file and buffer finder with regexp support.
 * [dbext.vim](https://github.com/vim-scripts/dbext.vim) - Provides database access to many dbms (Oracle, Sybase, Microsoft, MySQL, DBI,..)
 * [matchit.zip](https://github.com/vim-scripts/matchit.zip) - extended % matching for HTML, LaTeX, and many other languages

_That's 31 plugins, holy crap._