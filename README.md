# Dotfiles and Theme for Terminal.app

![Screenshot of my ternimal](https://i.imgur.com/zmAXYMn.jpg)

Some dotfiles and a theme for the default macOS Terminal app. Adds git information and tab completion.

### Based on:

### [Dotfiles by @mathiasbynens'](https://mths.be/dotfiles)

### [Solarized Dark Yosemite theme for terminal by @jcberthon] (https://github.com/jcberthon/solarized/blob/master/osx-terminal.app-colors-solarized/Solarized%20Dark%20Yosemite.terminal)

### [Shawn O. Pearce's git-completion](https://github.com/git/git/blob/master/contrib/completion/git-completion.bash)

## Installation

**Warning**: If you want to try the dotfiles, you should first fork this repository and review the code. Don't overwrite your .bashrc and .bash_prompt files! Use at your own risk.

Fork, clone or download the repository

Start the Terminal app and make sure you are in the home directory by typing `cd`

To view all the files including the dotfiles:

```bash
ls -a
```

Open `~/.bash_profile` with 

```bash
vim .bash_profile
```

or an editor of your choice and add the following to it:

```bash
if [ -f ~/.bashrc ]; then
	source ~/.bashrc
fi
```
This checks to see if `~/.bashrc` exists and will add it as a source.

Next open `~/.bashrc` with your favorite editor and copy the contents of the .bashrc file into it. Do the same for `~/.bash_profile`.

If you do not have a `~/.bash_profile` and a `~/.git_completion`, you can simply copy these files to your home directory.

Double clicking on the Solarized Dark Yosemite theme will add it as a profile to Terminal and you can then set it as the default.

