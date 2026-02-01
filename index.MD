# Tmux Cheatsheet

## [tmux session]

### _ new sessions
* `tmux`
* `tmux new`
* `tmux new-session`
* `tmux new -s sessionname`

### _ attach sessions
* `tmux a`
* `tmux att`
* `tmux attach`
* `tmux a -t sessionname`

### _ remove sessions
* `tmux kill-ses`
* `tmux kill-session -t sessionname`

### _ key bindings
* `ctrl` + `B` `$` : rename session
* `ctrl` + `B` `D` : detach session
* `ctrl` + `B` `)` : next session
* `ctrl` + `B` `(` : previous session

---

## [tmux windows]
*Windows are like tabs in a browser. Windows exist in a session and occupy the same session screen.*

### _ key bindings
* `ctrl` + `B` `C` : create window
* `ctrl` + `B` `N` : move to next window
* `ctrl` + `B` `P` : move to previous window
* `ctrl` + `B` `L` : move to last used window
* `ctrl` + `B` `0-9` : select window by number
* `ctrl` + `B` `'` : select window by name
* `ctrl` + `B` `.` : change window number
* `ctrl` + `B` `,` : rename window
* `ctrl` + `B` `F` : search windows
* `ctrl` + `B` `&` : kill window
* `ctrl` + `B` `W` : list windows

---

## [tmux panes]
*Panes are sections of windows that have been split into different screens — just like the panes on this cheatsheet.*

### _ key bindings
* `ctrl` + `B` `%` : vertical split
* `ctrl` + `B` `"` : horizontal split
* `ctrl` + `B` `→` : move to pane to the right
* `ctrl` + `B` `←` : move to pane to the left
* `ctrl` + `B` `↑` : move up to pane
* `ctrl` + `B` `↓` : move down to pane
* `ctrl` + `B` `O` : go to next pane
* `ctrl` + `B` `;` : go to last active pane
* `ctrl` + `B` `}` : move pane right
* `ctrl` + `B` `{` : move pane left
* `ctrl` + `B` `!` : convert pane to window
* `ctrl` + `B` `X` : kill pane

---

## [tmux copy mode] - EMACS MODE (DEFAULT)

### _ key bindings
* `ctrl` + `B` `[` : enter copy mode
* `ctrl` + `B` `]` : paste from buffer

### _ copy mode commands
* `ctrl` + `space` : start selection
* `ctrl` + `W` : copy selection
* `ctrl` + `G` : clear selection
* `alt` + `<` : go to top
* `alt` + `>` : go to bottom
* `←` `↑` `↓` `→` : move cursor
* `ctrl` + `S` : search
* `N` : next search
* `PageUp` : scroll page up
* `PageDown` : scroll page down
* `Q` : quit
