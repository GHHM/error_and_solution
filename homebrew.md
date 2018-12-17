## Error

Homebrew: /usr/local/share/man/man8 is not writable

brew update 에서 나타남.(MacOS 10.13 High Sierra)


## Solution

sudo chown -R $(whoami) /usr/local/share/man
