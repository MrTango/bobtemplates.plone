mr.bob tempates for Plone
=========================

for general instruction how to use mr.bob see:
http://mrbob.readthedocs.org/en/latest/index.html

Install bobtemplates.plone
--------------------------

Until we make a release on PyPi, you can install it like this:
::
   $ git clone git@github.com:MrTango/bobtemplates.plone.git
   $ cd bobtemplates.plone
   $ python setup.py install

You will probably do this in a virtualenv.

use bobtemplates.plone template
-------------------------------

you can use this template to create a new Plone addon like this:
::
   $ mkdir collective.mynewpackage
   $ cd collective.mynewpackage
   $ mrbob -c ~/.mrbob.ini bobtemplates:plone
