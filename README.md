Git Config
===========

checkout to ~/.config/git and adapt user-settings:

    git clone git://github.com/gimpf/dotgit ~/.config/git
    cp ~/.config/git/config-user-local.template ~/.config/git/config-user-local
    ${EDITOR:-vim} ~/.config/git/config-user-local

Doesn't do much except for setting up two pretty-formats, some aliases, and
use of kdiff3.

