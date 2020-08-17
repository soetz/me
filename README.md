# me
> The settings of my personal environment

## fonts

Install all the fonts in the `fonts` directory of this repo.

## shell

Install zsh + oh-my-zsh + the syntax highlighter plugin.

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

Put `.zsh-conf` from this repo inside the home folder.

## .me

Put `.me` from this repo inside the home folder.

Replace the content of `.zshrc` with only `source $HOME/.me`.