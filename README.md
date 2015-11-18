# utils
Common (composer based) tools we use at undpaul

## Installation

The collection is meant to be used globally by each team member. It has to be installed via [composer](https://getcomposer.org).

1. Make sure [composer is installed globalle](https://getcomposer.org/doc/00-intro.md)
1. Run `composer global require undpaul/utils:dev-master` to install globally.
1. Make sure `~/.composer/vendor/bin` is part of your `$PATH`, e.g. by adding
  `export PATH=~/.composer/vendor/bin:$PATH` to your `.bashrc`or `.profile`

## Update

After installing you can easily update to the latest version with `composer global update undpaul/utils`
