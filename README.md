# orhelper
orhelper is a module which aims to facilitate interacting and scripting with OpenRocket from Python.

## Prerequisites
- OpenRocket version 24.12 or above.  Ideally it will be installed in
  its default location, but running from non-default locations or from
  the .jar file are also supported.
  
- Python >= 3.6

- jpype1 >= 0.6.3

- numpy

The examples may have additional prerequites, for instance lazy.py
requires scipy and matplotlib

## Installing

- Install orhelper from pip
    ```bash
    pip install orhelper

- See `examples/` for usage examples

- See [the OpenRocket wiki](https://github.com/openrocket/openrocket/wiki/Scripting-with-Python-and-JPype) for more info on usage and the examples 

## Credits
- Richard Graham for the original script: [Source](https://sourceforge.net/p/openrocket/mailman/openrocket-devel/thread/4F17AA0C.1040002@rdg.cc/)
- @not7cd for some initial organization and clean-up: [Source](https://github.com/not7cd/orhelper)
- And of course everyone who has contributed to OpenRocket over the years.
