# tmux-conf
An simple and beautiful tmux configuration file.

## Install tmux

```bash
$ sudo apt-get update
$ sudo apt-get install -y python-software-properties software-properties-common
$ sudo add-apt-repository -y ppa:pi-rho/dev
$ sudo apt-get update
$ sudo apt-get install -y tmux=2.0-1~ppa1~t
```

## Config you tmux

1. Download `.tmux.conf` file.

```bash
$ git clone git@github.com:charleslxh/tmux-conf.git
```

2. Move `.tmux.conf` to `/home/user/`.

```bash
$ cd tmux-conf
$ mv .tmux.conf ~
```

## Start a tmux session

```bash
$ tmux new -s new-tmux-session
```

## Split a window

Press `Ctrl + prefix key`, then press `%`.

## Create a new window

Press `Ctrl + prefix key`, then press `c`.

## Use tmux tools.

- Tmuxinator: https://github.com/tmuxinator/tmuxinator

## use plugins

- tpm: https://github.com/tmux-plugins/tpm (tmux Plugin Manager)
- tmux-yank: https://github.com/tmux-plugins/tmux-yank (copying to system clipboard. Works on OSX, Linux and Cygwin.)
- tmux-sensible: https://github.com/tmux-plugins/tmux-sensible (basic tmux settings everyone can agree on)

## Example

![app-log](./app-log.png)
![editor](./editor.png)
