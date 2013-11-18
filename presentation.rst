Vim for the Win
===============

*Vim is about control*

*Getting more done with less keystrokes*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Vim is about touch typing
=========================

*Keep your fingers on the homerow*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Learning Vim
============

*Go Cold Turkey*
*Disable your arrow keys*
*Forget the mouse*

Use terminal Vim before you use Gvim/MacVim to learn to use the keyboard.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You are never done optimizing
=============================

Create a mapping to easily edit and reload your vimrc:

.. code-block:: vim

    nnoremap <leader>ev :vsplit $HOME/.vimrc<cr>
    nnoremap <leader>sv :source $HOME/.vimrc<cr>

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

An example
==========

*Quickly change your default color scheme*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Keep your dotfiles in version control
=====================================

    Edit -> commit -> push

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The Netrw File Explorer
=======================

* No need for Nerdtree
* Always open a directory listing relative to the file you are currently
  editing in that window

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Yank to and put from your clipboard
===================================

.. code-block:: vim

        " yank to the global system clipboard
        let s:uname = system("uname")
        if s:uname == "Darwin\n"
            " Do Mac stuff here
            set clipboard=unnamed
        else
            set clipboard=unnamedplus
        endif

Colors
======

Find yourself a nice color scheme or roll your own

.. code-block:: vim

        Bundle 'flazz/vim-colorschemes'

Tip: Have a look at these colorschem examples:
        http://vimcolorschemetest.googlecode.com/svn/html/index-html.html

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Search
======

*higlhighted search*
*use vimgrep to search in files*

.. code-block:: vim

    set incsearch                   " find as you type search
    set hlsearch                    " highlight search terms

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Use a plugin manager
====================

* Vundle by Gmarik https://github.com/gmarik/vundle
* Pathogen by Tim Pope https://github.com/tpope/vim-pathogen

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

SPF13
=====

A complete package of vim plugins to give you a quick start.

* spf13 https://github.com/spf13/spf13-vim

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Links
=====

* Steve Losh's blog
  http://stevelosh.com/blog/2010/09/coming-home-to-vim/
* Vimcasts
      http://vimcasts.org
* Touch typing links:
        Peter's Online Typing Course
          http://www.typing-lessons.org/
          Z-type
          http://phoboslab.org/ztype/
* Vimperator, a Firefox plugin
          http://www.vimperator.org/

Books
=====

Practical Vim by Drew Neill

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ask
===

Review this presentation on Github:

    https://github.com/markotibold/vim-for-the-win

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
