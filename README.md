# PyIFT


PyIFT is the Python wrapper of the libIFT, an image processing and machine learning library of
[The Laboratory of Image Data Science](http://lids.ic.unicamp.br/) of The University of Campinas.

The library is not fully available yet, precompiled files located at the `dist` directory give access to a subset of libIFT.

Available binary files were tested on Ubuntu 16.04 and Arch Linux with Python 3.5 and 3.7 respectively.

Binaries for other systems can be supplied upon request.

## Requeriments

* libpython\<version\>-dev
* Simplified Wrapper Interface Generator (SWIG)
* ...

## Installation

`sudo pip install pyift.-<version>-<python version>-<python lib version>-<system>.whl`

## Documentation

Documentation is not completely available, but a brief description of each function can be accessed as below:

```python
import pyift.pyift as ift

help(ift.ReadImageByExt)
```
