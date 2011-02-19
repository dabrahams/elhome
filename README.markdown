# ElHome - the _solvent_ Emacs configuration framework

"Keep it together"

## Installation

Evaluate this elisp.  You can copy it (to the clipboard or kill
ring such that `C-y' will insert it) and then `M-: C-y RET'

     (url-retrieve
       "https://github.com/dabrahams/elhome/raw/framework/elhome-install.el"
       (lambda (s) (end-of-buffer) (eval-print-last-sexp)))

## History

This project came out of my second
[.emacs bankruptcy](http://emacsblog.org/2007/10/07/declaring-emacs-bankruptcy/),
because the [first system](http://github.com/dabrahams/elisp) I had
set up had lost modularity and become too closely coupled with my own
configuration.

## Directories

* `~/.emacs.d/elhome/` - where everything related to this configuration is stored
* `~/.emacs.d/elhome/startup/` - elisp that is unconditionally loaded as
  early in startup as possible
* `~/.emacs.d/elhome/settings/` - settings for specific modes, including
  the general customization file settings.el
