# dotfiles

Franck Leroy's dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi).

Install chezmoi

```shell
sh -c "$(curl -fsLS get.chezmoi.io)" -- -b $HOME/.local/bin
```

Install dotfiles

```shell
chezmoi init leroyfranck --apply
```

To update chezmoi version :

```shell
chezmoi upgrade
```