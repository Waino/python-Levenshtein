.. contents ::

Introduction
------------

This fork extends the Levenshtein Python C extension module for fast
computation of

* Pairwise Levenshtein (edit) distance between two lists of strings

* Pruning thresholds using difference of string lengths and bag distance as lower bounds

The extensions *require* Unicode strings.

Python 2.7 or newer is required;

Documentation
--------------

gendoc.sh generates HTML API documentation,
you probably want a selfcontained instead of includable version, so run
in ``./gendoc.sh --selfcontained``.  It needs Levenshtein already installed
and genextdoc.py.

License
-----------

Levenshtein can be copied and/or modified under the terms of GNU General
Public License, see the file COPYING for full license text.


Source code
-----------

Source code available from github

* http://github.com/Waino/python-Levenshtein/

This is a fork of

* http://github.com/ztane/python-Levenshtein/

Authors
-------

* Author of fork: `Stig-Arne Grönroos <http://www.waino.org/>`

* Maintainer of original: `Antti Haapala <antti@haapala.name>`

* Python 3 compatibility: Esa Määttä

* Jonatas CD: Fixed documentation generation

* Previous maintainer: `Mikko Ohtamaa <http://opensourcehacker.com>`_

* Original code: David Necas (Yeti) <yeti at physics.muni.cz>
