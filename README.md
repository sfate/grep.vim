# grep.vim

This is a fork of the next [mirror](http://www.vim.org/scripts/script.php?script_id=311).

## Overview

Vim plugin for handy search through files.

## Installation

Follow the white rabbit to [wiki](https://github.com/Sfate/grep.vim/wiki/Installation)

## Usage

The grep.vim plugin introduces a lot Vim commands and you can find them [here](https://github.com/Sfate/grep.vim/wiki/Usage).

And we would start with theese two:

`:Grep`          - Search for the specified pattern in the specified files using grep

`:Ack`           - Search for the specified pattern in the specified files using ack

The above commands can be invoked like this:

    :Grep   [<grep_options>] [<search_pattern> [<file_name(s)>]]

    :Ack    [<grep_options>] [<search_pattern> [<file_name(s)>]]

In the above commands, all the arguments are optional.

## Configuration

Full list of configurations you can find [here](https://github.com/Sfate/grep.vim/wiki/Configuration)

For the quick start we will use just next ones(add them at your .vimrc):

    " Set executable path for ack
    let Ack_Path = 'ack-grep'

     " Enable showing up search results at new tab
    let Grep_OpenTabWithQuickfixWindow = 1

## [Changelog](https://github.com/Sfate/grep.vim/blob/master/changelog.md)

## License

The MIT License (MIT)

Copyright (c) 2013 Yegappan Lakshmanan
