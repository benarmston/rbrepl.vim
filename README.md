# RbREPL.vim

RbREPL.vim is a VIM plugin that allows you to run a Ruby interactive
interpreter inside a VIM buffer.

# Warning

*Multiline statements don't yet work.*

This plugin is in its early stages and I'm very new to Ruby programming.
It _probably_ won't do anything harmful to your computer, but it might,
at times, not work as expected. 

# Installation

Use `pathogen` and clone this repository into your `bundles` directory.

# Usage

Start the REPL using with `<leader>R` or `:RbREPLToggle<CR>`. Type away.
To stop the REPL run either of those commands again. This will not close
the buffer.
