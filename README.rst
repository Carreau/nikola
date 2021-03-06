Nikola, a Static Site and Blog Generator
========================================

In goes content, out comes a website, ready to deploy.

.. image:: http://img.shields.io/pypi/v/Nikola.png
   :target: https://pypi.python.org/pypi/Nikola

.. image:: https://requires.io/github/getnikola/nikola/requirements.png?branch=master
     :target: https://requires.io/github/getnikola/nikola/requirements/?branch=master

.. image:: http://img.shields.io/travis/getnikola/nikola.png
   :target: https://travis-ci.org/getnikola/nikola

.. image:: http://img.shields.io/coveralls/getnikola/nikola.png
  :target: https://coveralls.io/r/getnikola/nikola?branch=master

.. image:: http://img.shields.io/badge/license-MIT-green.png
   :target: https://github.com/getnikola/nikola/blob/master/LICENSE.txt

Why Static Websites?
--------------------

Static websites are safer, use fewer resources, and avoid vendor and platform lock-in.
You can read more about this in the `Nikola Handbook`_


What Can Nikola Do?
-------------------

It has many features, but here are some of the nicer ones:

* `Blogs, with tags, feeds, archives, comments, etc.`__
* `Themable`_
* Fast builds, thanks to `doit`_
* Flexible, extensible via plugins
* Small codebase (programmers can understand all of Nikola core in a day)
* `reStructuredText`_ or Markdown as input language (also Wiki, BBCode, Textile, and HTML)
* Easy `image galleries`_ (just drop files in a folder!)
* Syntax highlighting for almost any programming language or markup
* Multilingual sites, `translated to 18 languages.`__
* Doesn't reinvent wheels, leverages existing tools.
* Python 2.7, 3.3 and 3.4 compatible.

.. _Nikola Handbook: http://getnikola.com/handbook.html#why-static
__ http://users.getnikola.com/
.. _Themable: http://themes.getnikola.com
.. _doit: http://pydoit.org
.. _reStructuredText: http://getnikola.com/quickstart.html
.. _image galleries: http://getnikola.com/galleries/demo/
__ https://www.transifex.com/projects/p/nikola/

Nikola Architecture
-------------------
.. image:: /docs/architecture/nikola-architecture-draw-io.png

Installation Instructions
-------------------------

Assuming you have pip installed::

    pip install Nikola

For optional features::

    pip install Nikola[extras]

For tests (see tests/README.rst for more details)::

    pip install Nikola[extras,tests]

For more information, see http://getnikola.com/
