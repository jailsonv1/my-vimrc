
## Screenshots


## Plugins

vim uses [vim-plug](https://github.com/junegunn/vim-plug). Run `:PlugInstall` in vim to install all built-in plugins.

### Plugins list

## Utility
- [nerdtree][nerdtree] - The NERDTree is a file system explorer for the Vim editor. 
- [vim-commentary][vim-commentary] - Comment stuff out. 


## Theme
- [vim-airline][vim-airline] - lean & mean status/tabline for vim that's light as air
- [onedark.vim][onedark.vim] - A dark Vim/Neovim color scheme for the GUI and 16/256/true-color terminals 

### Move around & Edit

| Key            |      Mode      | Action                                  |
|:---------------|:--------------:|:----------------------------------------|
| `h`            |     Normal     | move current row to left                |
| `j`            |     Normal     | move the current line downward          |
| `k`            |     Normal     | move the current row up                 |
| `l`            |     Normal     | move the current row to the right       |
| `u`            |     Normal     | undo changes in Vim                     |
| `up`           |     Normal     | rezise +2 tab                           |
| `down`         |     Normal     | rezise +2 tab                           |
| `left`         |     Normal     | resize +2 tab                           |
| `right`        |     Normal     | resize +2 tab                           |
| `<Ctrl>` + `h` |     Normal     | resize the current split window         |
| `<Ctrl>` + `l` |     Normal     | resize the current split window         |
| `<Ctrl>` + `j` |     Normal     | resize the current split window         |
| `<Ctrl>` + `k` |     Normal     | resize the current split window         |
| `/` + `(text)` |     Normal     | search for the word type                |
| `<Ctrl>` + `i` |     Normal     | search for the word type                |

### Plugins key bindings

| Plugin                           | Key                      |      Mode     | Action                                                    |
|:---------------------------------|:-------------------------|:-------------:|:----------------------------------------------------------|
| [nerdtree][nerdtree]             | `Ctrl` + `n`             |     Normal    | Open and close an explorer the current directory          |
| [vim-commentary][vim-commentary] | `gcc`                    |     Normal    | to comment out a line                                     |
| [vim-commentary][vim-commentary] | `gc`                     |     Normal    | to comment out the target of a motion                     |
| [vim-commentary][vim-commentary] | `gcap`                   |     Normal    | to comment out a paragraph                                |
| [vim-commentary][vim-commentary] | `gc`                     |     Visual    | in visual mode to comment out the selection               |


[vim-airline]:https://github.com/bling/vim-airline "https://github.com/bling/vim-airline"
[onedark.vim]:https://github.com/joshdick/onedark.vim "https://github.com/joshdick/onedark.vim"
[nerdtree]:https://github.com/preservim/nerdtree  "https://github.com/preservim/nerdtree"
[vim-commentary]:https://github.com/tpope/vim-commentary  "https://github.com/tpope/vim-commentary"

