#vim | vi Cheatcode
######v0.0.0.0.1

This is a cheatcode|cheatsheet of some commands or tricks of vim/vi.

### Basic Commands
Command | Description | Similar commands
--- | --- | ---
`i` | Insert mode |
`Esc` | Command mode
`:w` | Write or save |
`:q` | Exit |
`:q!` | Exit with discard changes |
`:wq` | Save and Exit | `:x` , `ZZ`

### Movement Commands
Command | Description | Similar commands
--- | --- | ---
`h` | Move cursor to left | `left arrow key`
`j` | Move cursor to down | `down arrow key`
`k` | Move cursor to up | `up arrow key`
`l` | Move cursor to right | `right arrow key`
`$` | Move cursor to end of line |
`0` | Move cursor to first of line |
`w` | Forward cursor word by word | `W`
`b` | Backward cursor word by word | `B`
`:<num>` | Move cursor to line <num> |
`G` | Move cursor to last line of document |
`Ctrl+f` | Page Down |
`Ctrl+b` | Page up |

### Delete Commands
Command | Description | Similar commands 
--- | --- | ---
`x` | Delete char under cursor like as delete |
`X` | Delete char before cursor like as backspace |
`dw` | Delete word | 
`D` | Clean line content | 
`dd` | Delete line |
`<num>dd` | Delete <num> lines |
`dG` | Delete entire line below |

### Replacement Commands
Command | Description | Similar commands 
--- | --- | ---
`r` | Replace char with new char |
`R` | Replace mode ( Replace inserted chars until ESC pressed ) |

### Undo & Redo Commands
Command | Description | Similar commands 
--- | --- | ---
`:undo` | Undo | `u`
`:redo` | Redo | `Ctrl+r`
`U` | Undo all changes | 

### Copy & Past Commands
Command | Description | Similar commands 
--- | --- | ---
`yy` | Copy line |
`p` | Paste below line |
`P` | Paste after line |
`<num>yy` | Copy <num> lines |
`v` | Visual mode ( You can select and Copy with `y` or Cut `d` ) |

### Search & Replacement Commands
Command | Description | Similar commands 
--- | --- | ---
`/<string>` | Forward Search about <string> |
`?<string>` | Backward Search about <string> |
`:s/<lookup string>/<replacement string>` | Search & Replacement on nearest line just one time | 
`:%s/<lookup string>/<replacement string>` | Search & Replacement on multi lines just one time | 
`:s/<lookup string>/<replacement string>/g` | Search & Replacement on nearest line |
`:%s/<lookup string>/<replacement string>/g` | Search & Replacement entire of document | 
 

