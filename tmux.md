# tmux notes

## pane resizing

### Evenly size in one direction
`:select-layout even-vertical`
`:select-layout even-horizontal`

## scrollback

### Save current scrollback to file

```
:capture-pane -S -<lines>
:save-buffer <filepath>
```
