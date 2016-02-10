# Faster Key Repeat

By default, holding down a key brings up the accent menu.  We want to disable this in favor of a faster key repeat. We also want to set a blazingly fast keyboard repeat rate. The following commands are below:

Disable press-and-hold for keys in favor of key repeat
`defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool false`

Set a blazingly fast keyboard repeat rate
`defaults write NSGlobalDomain KeyRepeat -int 0`

Log out of your user account and then log back in for the change to take effect.

[source](https://github.com/mathiasbynens/dotfiles/blob/master/.osx#L183)
