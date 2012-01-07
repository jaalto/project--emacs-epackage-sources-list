Description
===========

This directory contains the **Yellow Pages** sources list file that
lists Emacs extensions that are available in *Distributed Emacs Lisp
Package System (DELPS)* or simply *Epackage* format.

The listed packages use Git Version Control System (DVCS) containers
for distribution. These epackage repositories, containers, can reside
anywhere publicly available. Their location is recorded in this
**yellow page** file to make them available for users. The person who
wraps Emacs extensions into containers is called epackage
*maintainer*. The person who is he author of the extension is called
*upstream*. These two can be the same or two separate people.

For more information see:

* DELPS at Emacs Wiki: http://www.emacswiki.org/emacs/DELPS
* Epackage main project hub: http://freshmeat.net/projects/emacs-epackage
* Epackage extension for Emacs: http://freshmeat.net/project/epackage
* Epackage manual: http://www.nongnu.org/emacs-epackage/manual
* Epackage template files: https://github.com/jaalto/project--emacs-epackage-template
* Epackage Yellow Pages: https://github.com/jaalto/project--emacs-epackage-sources-list

How To Contribute
=================

Fork this project and download the repository to your local disk. Add
new epackage information, commit to your github account and send a
*Pull request* through github. See these page:

- Forking a project: http://help.github.com/forking/
- Sending pull requests: http://help.github.com/pull-requests/

The information collected here include:

- PACKAGE-NAME -- from ``epackage/info::Package`` field.
- GIT-URL      -- the public git repository URL.
- DESCRIPTION  -- from 1st line from file ``epackage/info::Description``

After your changes have been been merged, update your copy::

    git pull

Copyright and License
=====================

Copyright (C) 2010-2012 Jari Aalto <jari.aalto@cante.net>

This material is free; you can redistribute and/or modify it under
the terms of GNU General Public license either version 2 of the
License, or (at your option) any later version.

End of file
