.. vim: set fileencoding=utf-8 :
.. Wed 17 Aug 16:25:52 CEST 2016

.. image:: http://img.shields.io/badge/docs-stable-yellow.png
   :target: http://pythonhosted.org/bob.db.cuhk_cufs/index.html
.. image:: http://img.shields.io/badge/docs-latest-orange.png
   :target: https://www.idiap.ch/software/bob/docs/latest/bob/bob.db.cuhk_cufs/master/index.html
.. image:: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs/badges/v2.1.0/build.svg
   :target: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs/commits/v2.1.0
.. image:: https://img.shields.io/badge/gitlab-project-0000c0.svg
   :target: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs
.. image:: http://img.shields.io/pypi/v/bob.db.cuhk_cufs.png
   :target: https://pypi.python.org/pypi/bob.db.cuhk_cufs
.. image:: http://img.shields.io/pypi/dm/bob.db.cuhk_cufs.png
   :target: https://pypi.python.org/pypi/bob.db.cuhk_cufs
.. image:: https://img.shields.io/badge/original-data--files-a000a0.png
   :target: http://mmlab.ie.cuhk.edu.hk/archive/facesketch.html

================================
CUHK Face Sketch Database (CUFS)
================================

This package is part of the signal-processing and machine learning toolbox
Bob_.
This package contains the access API and descriptions for the `CUHK Face Sketch Database (CUFS) <http://mmlab.ie.cuhk.edu.hk/archive/facesketch.html>`. 
The actual raw data for the database should be downloaded from the original URL. 
This package only contains the Bob accessor methods to use the DB directly from python, with the original protocol of the database.

CUHK Face Sketch database (CUFS) is for research on face sketch synthesis and face sketch recognition.
It includes 188 faces from the Chinese University of Hong Kong (CUHK) student database, 123 faces from the AR database, and 295 faces from the XM2VTS database.
There are 606 faces in total.
For each face, there is a sketch drawn by an artist based on a photo taken in a frontal pose, under normal lighting condition, and with a neutral expression.


Installation
------------

Follow our `installation`_ instructions. Then, using the Python interpreter
provided by the distribution, bootstrap and buildout this package::

  $ python bootstrap-buildout.py
  $ ./bin/buildout


Contact
-------

For questions or reporting issues to this software package, contact our
development `mailing list`_.


.. Place your references here:
.. _bob: https://www.idiap.ch/software/bob
.. _installation: https://gitlab.idiap.ch/bob/bob/wikis/Installation
.. _mailing list: https://groups.google.com/forum/?fromgroups#!forum/bob-devel
