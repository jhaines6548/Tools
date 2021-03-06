PNG2XYZ
=======

PNG2XYZ is a small tool to convert PNG images into RPG Maker 2000 and 2003 XYZ
image file format.

PNG2XYZ is part of the EasyRPG Project.
More information is available at the project website:

https://easyrpg.org/


Documentation
-------------

Documentation is available at the documentation wiki:

https://wiki.easyrpg.org/


Requirements
------------

 * libpng
 * zlib


Daily builds
------------

Up to date binaries for assorted platforms are available at:

https://ci.easyrpg.org/


Source code
-----------

PNG2XYZ development is hosted by GitHub, project files are available in Git
repositories.

https://github.com/EasyRPG/Tools


Building
--------

PNG2XYZ uses Autotools:

    ./bootstrap (only needed if using a git checkout)
    ./configure
    make
    make install (optionally)

You may tweak build parameters and environment variables, run
`./configure --help` for reference.


License
-------

PNG2XYZ is free software under the GNU General Public License Version 3. See
the file COPYING for details.
