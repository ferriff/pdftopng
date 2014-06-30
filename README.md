pdftopng
========

Convert a pdf image into a png of a configurable resolution.

## Installation

Clone the repository, change the permission of the executable (``chmod 755
pdftopng``) and enjoy.

Make sure you have the directory of the cloned repository in your ``PATH`` if
you don't want to specify the path of the executable each time you use it.
One way to do it is adding to your shell initialization file a line of the type

    export PATH="/your/cloned/repository:$PATH" # for sh-like  shells
    setenv PATH "/your/cloned/repository:$PATH" # for csh-like shells


## Dependencies

The program depends on the utils ``convert`` and ``pdftoppm``, which are found
on most common GNU/Linux distributions. For instance, on Debian they are
respectively in the ``imagemagick`` and ``poppler-utils`` packages.

## TODO

Improve the following:
* documentation
* verbosity/debugging options
