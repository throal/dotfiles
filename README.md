# althro's dotfiles

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/throal/dwm) (window manager)
- [dwmblocks](https://github.com/throal/dwmblocks) (statusbar)
- [st](https://github.com/throal/st) (terminal emulator)

## Install these dotfiles and all dependencies

Use [Cleveland Steamer](https://github.com/throal/cleveland-steamer) to autoinstall everything:

```
curl -LO git.io/cstmr
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/throal/cleveland-steamer/blob/master/progs.csv).
