# Disable Smart Quotes and Dashes

Curly quotations can become quite a problem if you are typing code into an text editor or an app like Evernote. Luckily they can easily be disabled by following these steps.

```bash
$ defaults write NSGlobalDomain NSAutomaticQuoteSubstitutionEnabled -bool false
$ defaults write NSGlobalDomain NSAutomaticDashSubstitutionEnabled -bool false
```

Log out of your user account and then log back in for the change to take effect.

[source](https://github.com/mathiasbynens/dotfiles/blob/master/.osx#L120)
