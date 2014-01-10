api-createaccount
=================

MediaWiki api-createaccount CLI client for testing

Requires PHP CLI installed. Assumes running on Mac OS X or other system where
running "open" command will launch an image viewer.

Requires core updates: https://gerrit.wikimedia.org/r/#/c/106844/

and ConfirmEdit updates: https://gerrit.wikimedia.org/r/#/c/106845/


Running
=======

Note that the URL is hardcoded, so change the MW_API_BASE constant in the
create-account file to match your local install.

  ./create-account

