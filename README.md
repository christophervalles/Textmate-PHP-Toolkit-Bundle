Repository moved
================

I moved the repository of this bundle to a new url to adapt it to the new name of the bundle.
If you have my bundle cloned you will have to modify it to fetch it from the new url.

The easy way to do it is just remove it and follow the instructions below.
If you want to choose the hard way you have to modify the file .git/config located inside the bundle
and change the url with the new one "git://github.com/christophervalles/Textmate-PHP-Toolkit-Bundle.git"

Description
===============

This is textmate bundle with a few useful snippets for PHP and HTML

* Avoid accidental close of Textmate asking if you want to close it.
* Shortcut to die(var_dump(RANDOM));
* Shortcut to die(var_dump());
* Shortcut to xdebug_break();
* Shortcut to trigger_error('Method ' . __METHOD__ . ' is deprecated');
* Tidy PHP scripts using php beautifier
* Show reference of actual PHP function
* Update the bundle itself
* Update the PHP reference documentation
* Built-in common php design patterns

How to install
==============

Execute the following commands:

    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/christophervalles/Textmate-Useful-Snippets-Bundle.git PHP\ Toolkit.tmbundle

Dependencies
============

You must have installed the following tools

* PHP Cli
* Tidy