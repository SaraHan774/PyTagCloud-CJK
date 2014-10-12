=============
 PyTagCloud
=============

PyTagCloud let you create simple tag clouds inspired by `Wordle <http://www.wordle.net/>`_.

This is a fork of `the original PyTagCloud <https://github.com/atizo/PyTagCloud>`_, that aims to support Korean. [1]_

Currently, the following output formats have been written and are working:

- PNG images
- HTML/CSS code


Requirements
============

#. Install `pygame <http://www.pygame.org/download.shtml>`_ >= 1.9.1::

    $ apt-get install python-pygame
    

Installation
============

Try::

    # pip install git+https://github.com/e9t/PyTagCloud.git

or::

    $ git clone git@github.com:e9t/PyTagCloud.git
    $ cd PyTagCloud
    # python setup.py install


Examples
========

- `Korean <examples/korean.py>`_::
    .. image:: examples/korean.png

- `Arabic <examples/arabic.py>`_::
    .. image:: examples/arabic.png


.. [1] A `pull request <https://github.com/atizo/PyTagCloud/pull/19>`_ has been sent to the original at Jun 11, 2014, and closed at Sep 2, 2014.
