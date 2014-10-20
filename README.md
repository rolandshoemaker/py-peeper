Peeper
======

A tool to extract requirements from a Python SDIST tarball/zip, so many funs!

Usage
-----


      rolands@ubuntu:~/peeper$ peeper.py ~/Downloads/zope.testing-4.1.3.tar.gz 
      [zope.testing-4.1.3 requires]
        setuptools
        zope.exceptions
        zope.interface
      rolands@ubuntu:~/peeper$ peeper.py -h
      usage: peeper.py [-h] [-n N] file

      Peep inside a Python sdist tarball/zip and find its dirty requirements.

      positional arguments:
      file        File to peep into.

      optional arguments:
      -h, --help  show this help message and exit
      -n N        Optional name of package, peeper will guess if not supplied
                  (needs to include version number if in tarball name.)
                  