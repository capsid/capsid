Installation
============
.. highlight:: bash

xeno-pipeline
--------------
**Xeno** is in the `Python Package Index
<http://pypi.python.org/pypi/xeno/>`_.

Dependencies
++++++++++++

**Xeno** requires the following packages to be installed:

* PyMongo_
* BioPython_
* pysam_
* bx-python_

Installation of these packages is not covered here. 

.. _PyMongo: http://api.mongodb.org/python/current/
.. _BioPython: http://biopython.org/wiki/Main_Page
.. _pysam: http://code.google.com/p/pysam/
.. _bx-python: https://bitbucket.org/james_taylor/bx-python/wiki/Home

Microsoft Windows
+++++++++++++++++

We recommend using the `MS Windows installers` available from the `Python
Package Index <http://pypi.python.org/pypi/xeno/>`_.

Installing with pip
+++++++++++++++++++

We prefer `pip <http://pypi.python.org/pypi/pip>`_
to install xeno on platforms other than Windows::

  $ pip install xeno

To get a specific version of xeno::

  $ pip install xeno==1.0

To upgrade using pip::

  $ pip install --upgrade xeno

Installing with easy_install
++++++++++++++++++++++++++++

If you must install xeno using
`setuptools <http://pypi.python.org/pypi/setuptools>`_ do::

  $ easy_install xeno

To upgrade do::

  $ easy_install -U xeno

Install from source
+++++++++++++++++++

If you'd rather install directly from the source (i.e. to stay on the
bleeding edge), check out the latest source from github::

  $ git clone git://github.com/xenobase/xeno-pipeline.git xeno
  $ cd xeno/
  $ python setup.py install

xeno-webapp
-----------

Dependencies
++++++++++++

**Xeno** is a web applications written in Grails_ and Groovy_ and requires a Java web server to run. Grails is only required if you wish to compile from source. 

.. _Grails: http://grails.org/
.. _Groovy: http://groovy.codehaus.org/

Installing
++++++++++

**Xeno** is released as a war file and needs to be moved to the webapps folder of your web server. For further instruction on how to properly use war files check the documentation of your web server.

Install from source
+++++++++++++++++++

If you'd rather install directly from the source (i.e. to stay on the
bleeding edge), check out the latest source from github::

  $ git clone git://github.com/xenobase/xeno-webapp.git xeno
  $ cd xeno/
  $ grails war
