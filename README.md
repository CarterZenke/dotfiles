Tutorial from <https://www.atlassian.com/git/tutorials/dotfiles>.

# Setup

```
mkdir .dotfiles
```

```
alias dotfiles='/usr/bin/git --git-dir $HOME/.dotfiles --work-tree=$HOME'
```

```
echo '.dotfiles' >> .gitignore
```

```
git clone --bare git@github.com:CarterZenke/dotfiles.git $HOME/.dotfiles
```

```
dotfiles checkout
```

```
dotfiles config --local status.showUntrackedFiles no
```
