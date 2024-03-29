Subset of image transformation, compression, and decompression codecs
=====================================================================

Imagecodecs-lite is a Python library that provides block-oriented, in-memory
buffer transformation, compression, and/or decompression functions for
LZW, PackBits, Delta, XOR Delta, Packed Integers, Floating Point Predictor,
and Bitorder reversal.

Imagecodecs-lite is a subset of the `imagecodecs
<https://pypi.org/project/imagecodecs/>`_ library, which provides additional
codecs for Zlib DEFLATE, ZStandard, Blosc, LZMA, BZ2, LZ4, LZF, AEC, ZFP,
PNG, WebP, JPEG 8-bit, JPEG 12-bit, JPEG SOF3, JPEG LS, JPEG 2000, and JPEG XR.

Unlike imagecodecs, imagecodecs-lite does not depend on external third-party
C libraries and is therefore simple to build from source code.

:Author:
  `Christoph Gohlke <https://www.lfd.uci.edu/~gohlke/>`_

:Organization:
  Laboratory for Fluorescence Dynamics. University of California, Irvine

:License: BSD 3-Clause

:Version: 2019.12.3

Requirements
------------
This release has been tested with the following requirements and dependencies
(other versions may work):

* `CPython 2.7.15, 3.5.4, 3.6.8, 3.7.5, 3.8.0 64-bit <https://www.python.org>`_
* `Numpy 1.16.5 <https://www.numpy.org>`_
* `Cython 0.29.14 <https://cython.org>`_

Notes
-----
The API is not stable yet and might change between revisions.

Works on little-endian platforms only.

Python 2.7, 3.5, and 32-bit are deprecated.

Build instructions for manylinux and macOS courtesy of Grzegorz Bokota.

Revisions
---------
2019.12.3
    Release manylinux and macOS wheels.
2019.4.20
    Fix setup requirements.
2019.2.22
    Initial release based on imagecodecs 2019.2.22.
