# dotfiles

Clone this repository to your home directory.

It assumes you have homebrew installed (see http://brew.sh)

Install homebrew-bundle by running `brew tap Homebrew/bundle`

Be sure to create a file called `.gitconfig` in your $HOME directory and include the configuration from this project by adding the following:

```
[include]
    path = .gitconfig.inherited
[user]
  name = 'Your Name'
  email = email@example.com
```

Then run `rake` from within this directory.

And finally run `brew bundle`

### credit

A good portion of the setup is stolen from https://github.com/peterkeen/dotfiles