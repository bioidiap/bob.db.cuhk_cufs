.. vim: set fileencoding=utf-8 :
.. Wed 17 Aug 16:25:52 CEST 2016

.. image:: https://img.shields.io/badge/docs-available-orange.svg
   :target: https://www.idiap.ch/software/bob/docs/bob/bob.db.cuhk_cufs/master/index.html
.. image:: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs/badges/master/pipeline.svg
   :target: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs/commits/master
.. image:: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs/badges/master/coverage.svg
   :target: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs/commits/master
.. image:: https://img.shields.io/badge/gitlab-project-0000c0.svg
   :target: https://gitlab.idiap.ch/bob/bob.db.cuhk_cufs

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

Complete Bob's `installation`_ instructions. Then, to install this package,
run::

  $ conda install bob.db.cuhk_cufs


Contact
-------

For questions or reporting issues to this software package, contact our
development `mailing list`_.


.. Place your references here:
.. _bob: https://www.idiap.ch/software/bob
.. _installation: https://www.idiap.ch/software/bob/install
.. _mailing list: https://www.idiap.ch/software/bob/discuss
