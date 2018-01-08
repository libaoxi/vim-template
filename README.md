Simple Vim templates plugin
=============================

**Author: Adrian Perez \<aperez@igalia.com>**

This is a simple plugin for Vim that will allow you to have a set of
templates for certain file types. It is useful to add boilerplate code
like guards in C/C++ headers, or license disclaimers.


Installation
============

The easiest way to install the plugin is to install it as a bundle,such as [vundle](https://github.com/gmarik/vundle),[vim-plug](https://github.com/junegunn/vim-plug).

**important:** If you use Fish__ as your shell, you *will* need to add

   ``set shell=/bin/sh`` to your ``~/.vimrc`` — the plugin relies on the
   setting pointing to a [Bourne-compatible](https://en.wikipedia.org/wiki/Bourne_shell) shell.

Documentation
=============

The documentation can be browsed directly in Vim::

    :help template.txt

Alternatively, you can also [read it in your browser](https://github.com/aperezdc/vim-template/blob/master/doc/template.txt).


Updating
========

Manually
--------

In order to update the plugin, go to its bundle directory and use
Git to update it:

1. ``cd ~/.vim/bundle/vim-template``

2. ``git pull``


With Vundle
-----------

Use the ``:BundleUpdate`` command provided by Vundle, for example invoking
Vim like this::

```
  % vim +BundleUpdate
```



