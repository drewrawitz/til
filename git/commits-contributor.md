# See how many commits each contributor has

This is a neat command that will show you how many commits each contributor has to the project. You can even turn this into an alias to make it easier to remember.

```git
$ git shortlog -sn
```

Let's make a `git stats` alias.

```git
$ git config --global alias.stats shortlog -sn
```

[source](https://twitter.com/csswizardry/status/707572922362241025)
