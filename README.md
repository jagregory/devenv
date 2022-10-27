# devenv setup

Sign in to the Mac App Store and your iCloud account before proceeding. You
need to be logged in for Brew to install Mac apps from the store.

Initial setup:

```sh
curl -sL https://raw.githubusercontent.com/jagregory/devenv/master/bootstrap | sh -
```

Enable Biometric Signin for the 1Password CLI then restore your secret files:

```sh
op-file-restore
```

## Manual tasks

1. Point iTerm2 to the symlinked config file (Settings > General > Preferences)
