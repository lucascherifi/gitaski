[![Latest Stable Version](https://poser.pugx.org/lucascherifi/gitaski/v/stable)](https://packagist.org/packages/lucascherifi/gitaski) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/lucascherifi/gitaski/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/lucascherifi/gitaski/?branch=master) [![Build Status](https://travis-ci.org/lucascherifi/gitaski.svg?branch=master)](https://travis-ci.org/lucascherifi/gitaski) [![License](https://poser.pugx.org/lucascherifi/gitaski/license)](https://packagist.org/packages/lucascherifi/gitaski)

Gitaski (stupid command)
========================

The purpose of this repository is quite stupid. It makes you a hardcoder. And you can giggle your friends.

Easy to use, just type a command to make your github commits list a funky thing.


## Quick install

1. Install:
```bash
$ composer global require lucascherifi/gitaski
```
Check that "It works!": `gitaski run --help` else take a look at the full documentation [here](https://github.com/lucascherifi/gitaski/blob/master/doc/install.md).

2. Create an empty git repository: [click here](https://github.com/new).

3. Run the command:

```bash
$ gitaski git@github.com:YOUR_PROFILE/AN_EMPTY_REPOSITORY_ALREADY_CREATED.git --use_text=Enjoy --force
```
Adapt with you own values ("YOUR_PROFILE", "AN_EMPTY_REPOSITORY_ALREADY_CREATED" and "Enjoy").

[![Enjoy](https://github.com/lucascherifi/gitaski/blob/master/doc/enjoy.png)](https://github.com/lucascherifi/gitaski/blob/master/doc/install.md)

Make good use and do not hesitate to contribute to this project.

More documentation
------------------
- [Install](https://github.com/lucascherifi/gitaski/blob/master/doc/install.md)
- [Usage](https://github.com/lucascherifi/gitaski/blob/master/doc/usage.md)
- [Contributing](https://github.com/lucascherifi/gitaski/blob/master/doc/contributing.md)

License
-------

This bundle is under the MIT license. See the complete license in the bundle:

    ./LICENSE