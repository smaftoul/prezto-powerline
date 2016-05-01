A [Prezto](http://github.com/sorin-ionescu/prezto) ZSH theme inspired by VIM Powerline that includes…

* … a single line prompt
* … project environment (java, node, ruby) and version (node, ruby)
* … compact git status, current git operation (rebase, cherry-pick, …), and time since last commit
* … most recent history event
* … indication of non-zero exit status
* … [base16](https://github.com/chriskempson/base16) compatible colors

![Example](https://raw.github.com/toolbear/prezto-powerline/master/prompt.png)

## Requires

* [Prezto ZSH](http://github.com/sorin-ionescu/prezto)
* A font [patched for Powerline](https://github.com/powerline/fonts)

## Conflict Indicators with verbose git info

In order to see conflict indicators (💥) you must have verbose git info enabled. Add the following to `~/.zpreztorc`:

```sh
zstyle ':prezto:module:git:info' verbose 'yes'
```

## Inspiration

* Original [Powerline for ZSH](https://github.com/davidjrice/prezto_powerline/) theme
* [Git Radar](https://github.com/michaeldfallen/git-radar)
