# vim-teraterm

This is a Vim plugin for Tera Term Language (TTL).
This includes an indent file and a syntax file.

License: VIM License

## Supported version

* [Tera Term](http://ttssh2.osdn.jp/index.html.en) 4.86

## Requirements

* Vim 7.4 or later.

## Usage

1. Add this directory to your 'runtimepath':

	:set runtimepath+=/path/to/vim-teraterm/

2. Create a file to detect the 'teraterm' file type.

   Create a file that contains the following line:

	au BufRead,BufNewFile *.ttl	set filetype=teraterm

   Save this file as `~/.vim/ftdetect/teraterm.vim`.

   See `:help ftdetect` for more detail.
