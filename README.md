## Install neovim

```bash
git clone git@github.com:neovim/neovim.git
cd neovim
sudo apt-get install ninja-build gettext cmake unzip curl build-essential
make CMAKE_BUILD_TYPE=RelWithDebInfo
sudo make install
```

## Setup XDG_CONFIG_HOME

```bash
export XDG_CONFIG_HOME=$HOME/.config
```

or open `~/.bashrc` and paste the line from above inside the file.
