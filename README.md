# Installation
Checkout this repository and symlink wanted files to your home directory.

	$ git clone https://github.com/mtarvainen/dotfiles.git
	$ ln -s dotfiles/.tmux.conf ~/
	$ ln -s dotfiles/.vimrc ~/
	
Additional files in the project (`.bash_profile` and `.bash_functions`) adds improved behaviour (eg. `ssh` hostname autocomplete) for bash.

## macOS

### Enable Solarized theme

#### iTerm2
iTerm2 include Solarized presets out-of-box. Apply it: iTerm2 -> Preferences -> Profiles -> Colors -> Color Presets -> Solarized Dark.

[Download iTerm2 here](https://www.iterm2.com/)

#### Terminal
Use [osx-terminal.app-colors-solarized](https://github.com/tomislav/osx-terminal.app-colors-solarized.git) preset.

    $ git clone https://github.com/tomislav/osx-terminal.app-colors-solarized.git

Add it as a new profile. Use it as a default theme: Terminal -> Preferences -> Solarized Dark -> Default.

More info [here](https://github.com/altercation/vim-colors-solarized#important-note-for-terminal-users).

#### .vimrc 
Disable degraded 256 colorscheme from `.vimrc` which is current default value.

    " let g:solarized_termcolors=256 

### Tmux
    $ brew install tmux
