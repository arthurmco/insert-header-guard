# insert-header-guard

This is an emacs plugin that inserts a header guard in a file.

This is my first emacs plugin, so bad elisp code is expected. If you want to enhance/fix it, feel free to do it.

We're not (yet) available in melpa. I don't know any plugin in melpa that does this already (and I searched it)

## Installation
 - Clone this repo
 - Copy that elisp file in your emacs.d folder
 - Put this block of code in your `.emacs` file
 
 ```elisp
(load "~/.emacs.d/insert-header-guard.el")
(require 'insert-header-guard)
(insert-header-guard-enable)
 ```
 
 Run it with `M-x insert-header-guard`
