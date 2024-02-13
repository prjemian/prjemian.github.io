.. Pete Jemian documentation master file, created by
   sphinx-quickstart on Mon Mar 24 21:27:55 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

..
   how to push this to github::

     make clean html
     pushd _build/html
     tar cf - . | (cd ../.. && tar xvf -)
     popd
     git add .
     git commit -am publish
     git push


Welcome to Pete Jemian's GitHub page!
=======================================

Various software projects are available.

  .. toctree::
     :hidden:

     gh-pages

..
  Indices and tables
  ==================

  * :ref:`genindex`
  * :ref:`modindex`
  * :ref:`search`

.. note:: Some of the links point to old documentation versions on ReadTheDocs.

..  TODO:
    dhtioc
    blnuhr
    readthedocs -> GH Pages
    murky
    pysumreg
    pyUB
    bdp_controls
    gpioc

Science
-------

* http://prjemian.github.io/sizes: analyze small-angle scattering data for a size distribution using maximum entropy
* http://prjemian.github.io/jldesmear: correct small-angle scattering data for slit-smearing
* https://github.com/prjemian/lake: previous C version of jldesmear
* https://github.com/prjemian/jlake: previous Java version of jldesmear

Bluesky framework
-----------------
* https://bcda-aps.github.io/apstools/latest/: APStools for Bluesky
* https://bcda-aps.github.io/bluesky_training/: training resources
* https://blueskyproject.io/hklpy/: Controls for using diffractometers within the Bluesky Framework.
* https://github.com/BCDA-APS/tiled-template: A template for a local tiled data server at the APS.
*

EPICS: Control Systems
----------------------

* https://github.com/prjemian/epics-docker: Provide EPICS IOCs in docker images
* http://epicsEdgeRoboArm.readthedocs.org: EPICS support for the OWI Edge Robotic Arm over USB (works on Raspberry Pi)
* http://pvMail.readthedocs.org: Watches an EPICS PV and sends email when value changes from 0 to 1.
* http://pvWebMonitor.readthedocs.org: post EPICS PVs to read-only (static) web page(s)
* http://prjemian.github.io/epicspi: Install EPICS on the Raspberry Pi
* http://prjemian.github.io/cmd_response: Arduino as I/O for EPICS (such as on Raspberry Pi)
* http://bcdaqwidgets.readthedocs.org: BcdaQWidgets: PyEpics-aware PySide widgets for the APS
* http://www.aps.anl.gov/bcda/synApps/optics/fb_epid use the EPICS *epid* record for generic software feedback

Utilities
---------

* http://HDF5gateway.readthedocs.org: IgorPro R/W support for HDF5 and NeXus data files
* http://spec2nexus.readthedocs.org: convert SPEC data files to NeXus
* http://specdomain.readthedocs.org: document SPEC macro files with Sphinx
* http://pyRestTable.readthedocs.org: format a nice table in reST from Python
* https://prjemian.github.io/punx/: Python Utilities for NeXus HDF5 files: validation, structure, hierarchy

Contributor
-----------

* http://nexusformat.org: NeXus data standard (documentation manager)
* http://www.cansas.org/formats/canSAS1d/1.1/doc: canSAS v1.1 data standard for 1-D small-angle scattering data
* http://www.cansas.org/formats/canSAS2012/1.0/doc/: canSAS draft data standard for any-D small-angle scattering data
* https://github.com/nexpy/nexpy: visualize NeXus data
* https://github.com/areaDetector: EPICS area detector support

Notes
-----

* :ref:`gh-pages`
* Some of my projects have documentation hosted at https://readthedocs.org (a.k.a. http://rtfd.org)
* GitHub: https://github.com/prjemian
* this: http://prjemian.github.io
* Ohloh: https://www.ohloh.net/accounts/Pete-R-Jemian
* PyPI projects: https://pypi.python.org/pypi?%3Aaction=search&term=jemian&submit=search
* published: |today|
