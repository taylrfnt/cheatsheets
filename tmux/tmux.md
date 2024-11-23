# tmux
## leader config
The default leader keybind is `Ctrl`+`b`; however, I configure the leader to be `Ctrl` + `Spc`, as
shown in the following `~/.config/tmux.conf` snippet:
```
# Custom Prefix key (Ctrl-Spc)
unbind C-b
set -g prefix C-Space
bind C-Space send-prefix
```

## sessions
### creating new sessions
| Action | Command/Keys |
| -- | -- |
| New session | `tmux` |
| New session | `tmux new` |
| New session with name | `tmux new -s sessionname` |

### attaching to existing sessions
```
tmux a
tmux att
tmux attach
tmux attach-session
tmux a -t sessionname
```

### navigating sessions
| Action | Command/Keys |
| -- | -- |
| `<leader>` + `$` | Rename session |
| `<leader>` + `)` | Next session |
| `<leader>` + `)` | Previous session |


### detaching from sessions
`<leader>` + `d`

###

