php-oauth
=========

This is the original reference implementation of OAuth in php, imported to git
using git-svn from https://code.google.com/p/oauth::

  git svn clone https://oauth.googlecode.com/svn/code/
  cd code
  git filter-branch --subdirectory-filter php -- --all

And then used the process described at https://help.github.com/articles/changing-author-info/ to rename the authors (myself, fangel and bpedro) to the email addresses used on their github profiles.

This project is un-maintained, the last maintainer was https://github.com/fangel and the original author was https://github.com/termie

Feel free to fork at will, there are quite a few implementations out there at this point, a few more won't hurt :)
