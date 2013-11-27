Introduction
============

A collection of [Alfred](http://www.alfredapp.com/) Workflows which I made/use.

<p align="center"><img src="http://upload.wikimedia.org/wikipedia/en/thumb/a/a4/Alfred-logo.png/289px-Alfred-logo.png" alt="Sublime text" width="250"></p>

Download
========

Download the folder by running

    git clone git@github.com:egrefen/alfred-workflows.git

or

    git clone https://github.com/egrefen/alfred-workflows.git

Installation
============

To install one of the workflows in the `./workflows` folder, simply double-click the `{workflow-name}.alfredworkflow` file to automagically import it into Alfred.

Available Workflows
===================

MacVim
------

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Vimlogo.svg/200px-Vimlogo.svg.png" alt="Sublime text" align="left" width="100" hspace=20> 
This assumes [MacVim](https://code.google.com/p/macvim/) is installed under `/usr/local/bin/mvim`. If it can't find that, it will back off to one of `/usr/bin/mvim`, `/usr/local/bin/gvim`, and finally `/usr/bin/gvim`.

This workflow allows you to open a file with MacVim (or just an empty buffer) by using one of the following keywords, followed by an optional argument (the path to the file):

* `macvim`
* `mvim`

Sublime Text
------------

<!-- <p align="left"> -->
<img src="http://upload.wikimedia.org/wikipedia/en/4/4c/Sublime_Text_Logo.png" alt="Sublime text" align="left" width="100" hspace=20>
This assumes [Sublime Text](http://www.sublimetext.com/) is installed in `/Applications`.

This workflow allows you to open a file with Sublime Text (or just an empty buffer) by using one of the following keywords, followed by an optional argument (the path to the file):

* `subl`
* `sublime`

Vim
------

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Vimlogo.svg/200px-Vimlogo.svg.png" alt="Sublime text" align="left" width="100" hspace=20>
This assumes [vim](http://www.vim.org/) is installed under `/usr/local/bin/vim`, or it will back off to `/usr/bin/vim`.

This workflow allows you to open a file with vim (or just an empty buffer) by using the keyword `vim` followed by an optional argument (the path to the file).