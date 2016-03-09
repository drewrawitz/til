# See how many commits each contributor has

This is a neat command that will show you how many commits each contributor has to the project.

```git
$ git shortlog -sn
```

You can even turn this into an alias to make it easier to remember. Let's make a `git stats` alias.

```git
$ git config --global alias.stats 'shortlog -sn'
```

[source](https://twitter.com/csswizardry/status/707572922362241025)
