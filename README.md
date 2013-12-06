# Installation

## Install the most recent version

Clone this repository somewhere

    $ cd ~/.emacs.d/plugins
    $ git clone --recursive https://github.com/capitaomorte/yasnippet

Add the following in your `.emacs` file:

    (add-to-list 'load-path
                  "~/.emacs.d/plugins/yasnippet")
    (require 'yasnippet)
    (yas-global-mode 1)

Add your own snippets to `~/.emacs.d/snippets` by placing files there or invoking `yas-new-snippet`.

# How to use

1. install yasnippet
2. add to your .emacs the following
   - (add-to-list 'yas/root-directory "$DIRECTORY_WHERE_YOU_CLONED")
   - (yas/initialize)
3. M-x yas/reload-all to activate them