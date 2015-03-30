vim-modelica
============

Snippet, detection and other goodies to edit modelica (.mo) files

## Installation Vundle 
Install [Vundle](https://github.com/gmarik/Vundle.vim) if not already installed.

Then add
```vim
Plugin 'drmingdrmer/xptemplate'
Plugin 'Twinside/vim-modelica'
```
to the .vimrc . And type :PluginInstall in the ex command line of the vim.

## Usage
You can type the following short hands with `shorthand``<ctrl+\>`. 

For example `block<ctrl+\>` yields:
```
block `blockName^
    `cursor^
end `blockName^;
```

You may use `<tab>` to navigate through the elements (`blockName`, `cursor`).

## About
Requires [drmingdrmer/xptemplate](https://github.com/drmingdrmer/xptemplate) to work.
