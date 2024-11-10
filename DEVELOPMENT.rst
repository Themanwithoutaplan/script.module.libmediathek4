Setting up a development environment outside Kodi
=================================================

In order to use this library in other code, you need to add it to the Python path:

`export PYTHONPATH=path/to/libmediathek/lib`

As the library itself depends upon various modules from XBMC, you'll also need
to install the kodistubs package:

`pip install kodistubs`

Check the documentation for these https://romanvm.github.io/Kodistubs/

Some calls expect a value from `sys.argv` so you may need to insert a relevant integer at index 1