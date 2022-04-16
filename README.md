##  TMUX CHEATSHEET

### 1. Windows

####    Start a new session
```sh
$ tmux new -s (SESSION-NAME)
```

####    Start a new session with the name mysession and window mywindow
```sh
$ tmux new -s (SESSION-NAME) -n (WINDOW-NAME)
```

####    Create window
```sh
ctrl + b   c
```

####    Rename current window
```sh
ctrl + b   ,
```

####    Close current window
```sh
ctrl + b   &
```

####    Previous window
```sh
ctrl + b   p
```

####    Next window
```sh
ctrl + b   n
```

####    Switch/select window by number
```sh
ctrl + b   0 ... 9
```

####    Move current window to the left by one position
```sh
:swap-window -t -1
```

####    Reorder window, swap window number 2(src) and 1(dst)
```sh
:swap-window -s 2 -t 1
```
