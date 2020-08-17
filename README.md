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
Put the content of the `zsh-themes` folder of this repo inside the <HOME>/.oh-my-zsh/custom/themes folder.

## .me

Put `.me` from this repo inside the home folder.

Replace the content of `.zshrc` with only `source $HOME/.me`.

## .aliases

Put `.aliases` from this repo inside the home folder.

## ruby

Install `rvm`.

```
sudo apt-get install software-properties-common
sudo apt-add-repository -y ppa:rael-gc/rvm
sudo apt-get update
sudo apt-get install rvm
```

Reboot.

Install a ruby.

```
rvm install ruby
```

## colorls

Install `colorls`.

```
gem install colorls
```
