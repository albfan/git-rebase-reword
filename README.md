# git-rebase-reword

git-rebase-reword is a simple git command to change one commit (last or older) the same way as you ammend

## Documentation

It is named after the action on rebase interactive to ammend a commit "reword". See [this post](https://robots.thoughtbot.com/git-interactive-rebase-squash-amend-rewriting-history) and [git rebase man](http://git-scm.com/docs/git-rebase) -section interactive mode-
##Install

Download and symlink to your path

```bash
$ git clone https://github.com/albfan/git-rebase-reword.git
$ cd git-rebase-reword
$ ln -s $PWD/git-rebase-reword ~/bin/
$ ln -s $PWD/reword_editor ~/bin/
```

##Usage

```bash
$ cd <repo>
$ git rebase-reword <commit|symbolic-ref>
```

