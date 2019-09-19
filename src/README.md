## Build Instructions

### Python 2.7

The `python27/` directory contains an unmodified Python 2.7.15 source release downloaded from https://www.python.org/downloads/release/python-2715/.

From `python27/`:

    mkdir ../../python27
    ./configure --enable-optimizations --with-ensurepip=install --prefix=`pwd`/../../python27
    make install

This will build and install a Python 2.7 release in a `python27/` directory at the root of the repository.
