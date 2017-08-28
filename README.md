# Laptop
======

This is a script to set up a macOS laptop for development.

Specifically, _my_ macOS laptop!

This is a fork of a [similar script by CodeClan](https://gothub.com/codeclan/laptop), itself a fork of a script by ThoughtBot

## Install

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/codeclan/laptop/master/mac
```
Then:
```sh
sh mac 2>&1 | tee ~/laptop.log
```

## Debugging

What it sets up
---------------

macOS tools:

* [Homebrew](http://brew.sh/) for managing operating system libraries.

Unix tools:

* [Git] for version control
* [Zsh] as your shell
* [wget] for downloading files from the Terminal

[Git]: https://git-scm.com/
[Zsh]: http://www.zsh.org/
[wget]: https://www.gnu.org/software/wget/

Programming languages and configuration:

* [Bundler] for managing Ruby libraries
* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [Rbenv] for managing versions of Ruby
* [Ruby Build] for installing Rubies
* [Ruby] stable for writing general-purpose code
* [Java] and [Junit] for compiling, running and testing Java code

[Bundler]: http://bundler.io/
[Node.js]: http://nodejs.org/
[NPM]: https://www.npmjs.org/
[Rbenv]: https://github.com/sstephenson/rbenv
[Ruby Build]: https://github.com/sstephenson/ruby-build
[Ruby]: https://www.ruby-lang.org/en/
[Java]: https://java.com/en/
[Junit]: http://junit.org/

Databases:

* [Postgres] for storing relational data
* [MongoDB] for storing non-relational data

[Postgres]: http://www.postgresql.org/
[MongoDB]: https://www.mongodb.com/

GUI Apps:

* Google Chrome for web browsing
* Atom for text editing
* Slack for team chat
* Android Studio for mobile development
* iTerm2 for a more pleasant Terminal experience
* Native Access for installing Native Instruments plugins
* Spotify because music is life

Fonts:
* Source Code Pro for accessibility

Finally, we remap the `§` key on your Mac's keyboard to the `#` symbol, which can make commenting Ruby marginally less painful...

It should take less than 15 minutes to install (though this depends on your machine).

About CodeClan
--------------

![CodeClan](https://codeclan.com/wp-content/uploads/2016/03/favicon.png)

See [our website](https://codeclan.com) for more information.
