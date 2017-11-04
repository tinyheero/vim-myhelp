# Fong's Vim Help

This is my personal Vim cheatsheet. The idea for this was 
[original from technosophos](https://github.com/technosophos/vim-myhelp).

## To Install

The cheatsheet gets added as a plugin. So if you use a plugin manager like 
[vim-plug](https://github.com/junegunn/vim-plug), you can add the following to 
your `~/.vimrc` or `~/.config/nvim/init.vim` 

```
Plug 'tinyheero/vim-myhelp'
```

You then need to run the command (if using neovim):

```
helpt ~/.config/nvim/plugged/vim-myhelp
```

If you are using normal vim, you will need to find where the plugin gets 
installed and replace the above path with the correct path.

After this restart vim/neovim and you should be able to type `:h myhelp` and 
the following should appear.
