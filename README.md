GIT-PERMISSION-FIX
==================

This will correct any variation in file permissions between the current working directory and the index.

This does check that some permission changes actually exist, and will exit with failure if none can be found.

Installation
------------

Clone the repository and put git-permission-fix in a folder on your path, or add the repository folder to your path.

You can also install this using [antigen](https://github.com/zsh-users/antigen), like so:

    antigen-bundle matthewfranglen/git-permission-fix

Useage
------

Once correctly installed it should just be a case of calling:

    git permission-fix
