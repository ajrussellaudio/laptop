# Laptop

This is a script to set up a macOS laptop for development.

Specifically, _my_ macOS laptop!

This is a fork of a [similar script](https://gothub.com/codeclan/laptop) by [CodeClan](http://codeclan.com), which was itself a fork of a script by some little company called ThoughtBot.

## Install

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/codeclan/laptop/master/mac
```
Then:
```sh
sh mac 2>&1 | tee ~/laptop.log
```

## What it sets up

### macOS tools:

* [Homebrew](http://brew.sh/) for managing operating system libraries.
* [Xcode](https://developer.apple.com/xcode/), which apparently you can't do anything on macOS without.

### Command line tools:

* [Git](https://git-scm.com/) for version control
* [Zsh](http://www.zsh.org/) as your shell
* [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) because we don't hate you
* [wget](https://www.gnu.org/software/wget/) for downloading files from the Terminal

### Programming languages and configuration:

* [Ruby](https://www.ruby-lang.org/en/) for writing general-purpose code
* [Rbenv](https://github.com/sstephenson/rbenv) for managing versions of Ruby
* [Bundler](http://bundler.io/) for managing Ruby libraries
* [Ruby Build](https://github.com/sstephenson/rbenv) for installing Rubies
* [Java](https://java.com/en/) and [Junit](http://junit.org/) for compiling, running and testing Java code
* [Node.js](http://nodejs.org/) for JavaScript back-end development, and
* [NPM](https://www.npmjs.org/) for installing JavaScript packages

### Databases:

* [PostgreSQL](http://www.postgresql.org/) for storing relational data
* [MongoDB](https://www.mongodb.com/) for storing non-relational data

### GUI Apps:

* [Google Chrome](https://www.google.com/chrome/) for web browsing and development
* [Atom](https://atom.io/) for text editing
* [Slack](https://slack.com) for team chat
* [Android Studio](https://developer.android.com/studio/index.html) for mobile development
* [iTerm2](https://www.iterm2.com/) for a more pleasant Terminal experience
* [Native Access](https://www.native-instruments.com/en/specials/native-access/) for installing Native Instruments plugins
* [Spotify](https://www.spotify.com/) because music is life

### Fonts:
* [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) because it makes my eyes happy

Finally, we remap the `§` key on your Mac's keyboard to the `#` symbol, which can make commenting Ruby marginally less painful...

It should take less than 15 minutes to install (though this depends on your machine).
