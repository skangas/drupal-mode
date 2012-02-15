# Drupal Mode #

Drupal Mode is an advanced minor mode for developing in Drupal.

Drupal Mode is based on top of PHP mode and defines among other things
indentation etc. to match Drupal Coding Standards.

## Mission statement ##

* Don't over do it
    * Only provide what makes sense in standard Emacs fashion.
    * Leave out what is considered personal taste.
    * Provide optional stuff if in doubt.
    * ... or provide option to disable if the personal taste is considered good practice.
    * The rest can go as advice on EmacsWiki or github wiki or g.d.o.
* Lets base this on Emacs 24 - to do it simple, backporting can come later.
* Do the right thing in all relevant major modes:
	* php-mode
	* javascript mode(s)
	* conf-mode (module.info)
* Provide the mode via ELPA.

## Other drupal modes ##

There are quite a few attempts at writing a drupal-mode out in the
wild:

* [Search Github for drupal-mode](https://github.com/search?type=Repositories&q=drupal-mode)
* At drupal.org:
	* http://drupal.org/sandbox/bartlantz/1405156
	* http://drupal.org/project/emacs

All of them more or less based on
[Configuring Emacs](http://drupal.org/node/59868).

## Installation ##

The easiest way to install Drupal Mode is probably to install it via
the ELPA archive at [Marmalade](http://marmalade-repo.org/packages/drupal-mode).
