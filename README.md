ImageSlicer
===========

ImageSlicer is a simple utility designed to slice arbitrarily large images into small tiles suitable for tiled printing. 

Requirements
------------

ImageSlicer relies on [PIL](http://www.pythonware.com/products/pil/), which can be installed by running "pip install PIL" at the command line.

Usage
-----

ImageSlicer can be called by running the following:

    python ImageSlicer.py [-h] -p width height -w width height [-v] filename

Here, `width` and `height` following the `-p` flag refer to the width and height of a single sheet of paper, in inches. `width` and `height` following the `-w` flag refer to the width and height of the total output size, in feet.

The optional `v` flag can be used to increase verbosity. Calling `vv` reveals additional debugging information.


Happy slicing!