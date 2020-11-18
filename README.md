# cyberpunk.nvim
My custom Cyberpunk NeoVim theme. Put the ```cyberpunk.vim``` file into the ```colors``` folder of nvim and add the following line to your ```init.vim``` file: ```autocmd vimenter * colorscheme cyberpunk```

## vim-plug

Add the following to your ```.vimrc``` or ```init.vim```:

```
call plug#begin()
Plug 'ayaz-amin/cyberpunk.nvim' , {'branch' : 'main'}
call plug#end()

autocmd vimenter * colorscheme cyberpunk
```
