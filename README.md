Files are explanied briefly below. Contributions and suggestions/issues are always welcome.

## Emacs

[Setup script](emacs/setup.sh) does the following:

- Copies config files to `$HOME/.emacs`
- Installs and activates [elpy](https://github.com/jorgenschaefer/elpy), a Python plugin from MELPA: - Creates a virtual environment for Python to `$HOME/.emacs/py3venv` - Installs elpy's required packages with pip - If you're using macOS, installs [another plugin from MELPA](https://github.com/purcell/exec-path-from-shell) to access shell and activate virtual environment in GUI mode

Note: Configuration sets a specific font, currently [Source Code Pro](https://github.com/adobe-fonts/source-code-pro), configuration won't load for GUI client unless your OS has the font. You may download the font or change the configuration.

## Zsh

[Setup script](vim/setup.sh) does the following:

- Installs zsh to path
- Clones [zsh repository](https://github.com/robbyrussell/oh-my-zsh) to `$HOME/.oh-my-zsh`
- Copies .zprofile and .zshrc to `$HOME`
- Asks you if you want to make zsh your default shell

**Note:** You can't use this on Windows.

## Vim

[Setup script](vim/setup.sh) does the following:

- Copies config files according to your OS
- Installs colorschemes from [github/awesome-vim-colorschemes](https://github.com/rafi/awesome-vim-colorschemes)

## PyPI

Contains templates:

- [.pypirc](pypi/template.pypirc)
- [Example script](pypi/upload.sh) that uploads to test index.

## SSH

Contains template of [config file](ssh/config_template) with explanations.

## Bash

[Setup script](bash/setup.sh) copies .bash_profile and .bashrc to `$HOME`.
