runcommand/precache
===================

Proactively download and cache core, theme, and plugin files for later installation.

[![runcommand open source](https://runcommand.io/wp-content/themes/runcommand-theme/bin/shields/runcommand-open-source.svg)](https://runcommand.io/pricing/) [![Build Status](https://travis-ci.org/runcommand/media-sizes.svg?branch=master)](https://travis-ci.org/runcommand/media-sizes)

Quick links: [Using](#using) | [Installing](#installing) | [Support](#support)

## Using

This package implements the following commands:

### wp precache core

Proactively download and cache WordPress core.

~~~
wp precache core [--version=<version>] [--locale=<locale>]
~~~

**OPTIONS**

	[--version=<version>]
		Specify the version to cache.

	[--locale=<locale>]
		Specify the language to cache.



### wp precache plugin

Proactively download and cache one or more WordPress plugins.

~~~
wp precache plugin [<plugin>...] [--version=<version>]
~~~

**OPTIONS**

	[<plugin>...]
		One or more plugins to proactively cache.

	[--version=<version>]
		Specify the version to cache.



### wp precache theme

Proactively download and cache one or more WordPress themes.

~~~
wp precache theme [<theme>...] [--version=<version>]
~~~

**OPTIONS**

	[<theme>...]
		One or more themes to proactively cache.

	[--version=<version>]
		Specify the version to cache.

## Installing

Installing this package requires WP-CLI v0.23.0 or greater. Update to the latest stable release with `wp cli update`.

Once you've done so, you can install this package with `wp package install runcommand/precache`.

## Support

This WP-CLI package is free for anyone to use. Support, including usage questions and feature requests, is available to [paying runcommand customers](https://runcommand.io/pricing/).

Think you’ve found a bug? Before you create a new issue, you should [search existing issues](https://github.com/runcommand/sparks/issues?q=label%3Abug%20) to see if there’s an existing resolution to it, or if it’s already been fixed in a newer version. Once you’ve done a bit of searching and discovered there isn’t an open or fixed issue for your bug, please [create a new issue](https://github.com/runcommand/sparks/issues/new) with description of what you were doing, what you saw, and what you expected to see.

Want to contribute a new feature? Please first [open a new issue](https://github.com/runcommand/sparks/issues/new) to discuss whether the feature is a good fit for the project. Once you've decided to work on a pull request, please include [functional tests](https://wp-cli.org/docs/pull-requests/#functional-tests) and follow the [WordPress Coding Standards](http://make.wordpress.org/core/handbook/coding-standards/).

runcommand customers can also email [support@runcommand.io](mailto:support@runcommand.io) for private support.


