# helm-addressbook

Helm interface to [addressbook-bookmark](https://github.com/thierryvolpiatto/addressbook-bookmark)

# Install from sources

## Dependencies

- [Helm](https://github.com/emacs-helm/helm)
- [addressbook-bookmark](https://github.com/thierryvolpiatto/addressbook-bookmark)

## Install

Just add helm-addressbook.el to one directory of your `load-path` and byte-compile it.
Add an autoload declaration of `helm-addressbook-bookmarks` in your init file or just require helm-addressbook.el.

# Usage

You first have to add contacts to your bookmark files, see instructions at [addressbook-bookmark](https://github.com/thierryvolpiatto/addressbook-bookmark).
Then M-x helm-addressbook-bookmarks will show you your contacts.
For general helm usage please see helm documentation [on line](https://github.com/emacs-helm/helm/wiki) or with `C-h m` while in your
helm-addressbook session.
