# pt_black
pt_black(putty_tmux_black) only provides a simple display color with command line user and putty user.


### Prefect way
- Install [Vundle plugin manager](http://github.com/gmarik/Vundle.vim):
```
Plugin 'yantze/pt_black'
```
- Change windows putty color.(remember load [pt_black] setting on putty.exe)

Run file `pt_black_putty_color_setting.reg` 

- Use in Tmux
```
# run in 256 colors mode
tmux -2
```

- Use in Vim
```
# open vim then
:color pt_black
```


###How To Use pt_black?

Use the command `:color pt_black`


###How To Set pt_black as your Default Color Scheme?

Add the following Line to your _vimrc or .vimrc File:

```
colorscheme pt_black
```

### How To Install pt_black?

Save the file as "colors/pt_black.vim" under your ".vim" directory

i.e. as `~/.vim/colors/pt_black.vim` .

### Use in putty

run the `pt_black_putty_color_setting.reg` file on windows.


*Screenshots:*


![pt_black](https://raw.github.com/yantze/pt_black/master/screenshot/Screenshot_1.png)

### Contributions
Always welcome.

### Thanks
Base on ir_black.vim
