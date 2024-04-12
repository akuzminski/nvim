# Install neovim

```bash
git clone git@github.com:neovim/neovim.git
cd neovim
sudo apt-get install ninja-build gettext cmake unzip curl build-essential
make CMAKE_BUILD_TYPE=RelWithDebInfo
sudo make install
```
