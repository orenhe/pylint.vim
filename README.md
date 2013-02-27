Installation
============
1. Get the plugin
-----------------
Using Pathogen https://github.com/tpope/vim-pathogen:

    cd ~/.vim/bundle
    git clone git://github.com/orenhe/pylint.vim.git

Manually:

    cd ~/.vim/compiler
    wget http://raw.github.com/orenhe/pylint.vim/master/compiler/pylint.vim

2. Setup ~/.vimrc
-----------------
To get Vim to auto-recognize pylint as Python's compiler, add the following line to your `~/.vimrc`:

    autocmd FileType python compiler pylint


Troubleshooting
===============
Make sure you have pylint installed (easy\_install pylint / apt-get install pylint).
Validate that `pylint <python file>` command works as expected.



Fork history
============
This was forked by Oren Held (2011), from the version of:
http://code.google.com/p/vim-python-ide/

which is probably based on
http://www.vim.org/scripts/script.php?script\_id=891

and possibly older predecessors.

Credits are inside pylint.vim file.


Feedback
========
Post bugs, ideas and pull requests to http://github.com/orenhe/pylint.vim
