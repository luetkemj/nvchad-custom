## Install NvChad 

[Installation instructions](https://nvchad.com/docs/quickstart/install)

## Install this repo

navigate to nvchad config (neovim config)

`cd ~/.config/nvim/lua`

remove existing custom dir if it exists

`rm -rf ./custom`

clone repo

`git clone git@github.com:luetkemj/nvchad-custom.git custom`

restart nvim

### gotchas and other misc

If using iterm2 make sure to update the Keys setting under your current profile to enable the `alt` key to work. There are several default nvChad mappings that rely on the key and by default, iTerm2 treats opt/alt as opt causing these mappings to fail silently.
