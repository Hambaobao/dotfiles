# Dotfiles

Personal dotfiles managed with [GNU Stow](https://www.gnu.org/software/stow/).

## Structure

Each directory is a stow package:

```
dotfiles/
├── zsh/
│   └── .zshrc
└── ...
```

## Usage

Clone the repo and run `stow` to symlink a package to `$HOME`:

```bash
git clone <repo-url> ~/workspace/dotfiles
cd ~/workspace/dotfiles
stow zsh
```

To remove a package:

```bash
stow -D zsh
```
