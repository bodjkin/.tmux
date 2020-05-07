# .tmux

## Setup:

We clone this into our home directory and pick a config file. The `.tmux.conf`
file is for servers; the `.tmux-dev.conf` file is for local use.

We install the development file with:

`ln -s ~/.tmux/.tmux-dev.conf ~/.tmux.conf`

*or* the server file with:

`ln -s ~/.tmux/.tmux.conf ~/.tmux.conf`.

Then we set up the plugin manager:

`git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

To install the other plugins, we start up tmux, press F8, then *capital* I, and
then we wait a few moments for it to finish.
