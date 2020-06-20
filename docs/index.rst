###################################################################
SetupSkyLOSA: A MATLAB Tool to support Acquisition of Sky-LOSA Data
###################################################################

.. include:: ../README.rst
  :start-after: abstract-start
  :end-before: abstract-end

.. toctree::
  :caption: Detailed Instructions
  :maxdepth: 3

  Instructions for use <instructions>

****************
Citation and Use
****************

*SetupSkyLOSA* is described in a discussion article currently under open-review in `Atmospheric Measurement Techniques Discussions <https://www.atmos-meas-tech-discuss.net/>`_ and is shared free of charge under the :ref:`MIT license <AnchorToLicense>`.  When using the software for the acquisition of data in published work, it is requested that users cite/acknowledge the following:

  .. include:: ../README.rst
    :start-after: masterref-start
    :end-before: masterref-end

********
Features
********

.. include:: ../README.rst
  :start-after: features-start
  :end-before: features-end

***************************
Installation & Requirements
***************************

Source and build (standalone executable and packaged MATLAB app) distributions of *SetupSkyLOSA* are hosted on `GitHub <https://github.com/bradleymconrad/SetupSkyLOSA>`_. Software data are too large to house completely on GitHub but are available in the **latest release**. If a release has not yet been created for the latest version, please `contact the author <mailto:brad.m.conrad@gmail.com>`_ for the latest complete source and/or build versions.

.. note::

  If you encounter issues during installation or when using *SetupSkyLOSA*, please `contact the author <mailto:brad.m.conrad@gmail.com>`_.

Source Distribution
===================

If you have a MATLAB license, add the entire "source" directory to the MATLAB path and run "SetupSkyLOSA". The software was developed in MATALB R2019a and uses the **Image Processing** and **Statistics and Machine Learning** toolboxes. To clone the *SetupSkyLOSA* repository, see GitHub's `instructions <https://help.github.com/en/articles/cloning-a-repository>`_.

Build Distributions
===================

Build distributions are provided as a standalone executable and a packaged MATLAB app.

Standalone Executable
---------------------

To install the *SetupSkyLOSA* executable, double-click the "SetupSkyLOSA_Installer" executable (.exe file) in the "build" directory.

.. note ::

   MATLAB unpackages the Runtime and executable to a temporary folder on each boot of the software. To speed up booting, the user can direct MATLAB to unpackage the Runtime and executable once in a defined location. The user can create a folder to house the unpackaged data (approximately 1.1 GB) and define an environment variable called **MCR_CACHE_ROOT** that links to the folder. The MCR_CACHE_ROOT folder should be located on the fastest available hard drive.

.. note::

  When booting the software, the landing screen may disappear and it may seem as though booting has stalled. Be patient at this point; the MATLAB Runtime is being loaded and *SetupSkyLOSA* will initialize shortly after.

Packaged MATLAB App
-------------------

To install the packaged *SetupSkyLOSA* MATLAB app, double-click the "SetupSkyLOSA_Installer" app installer (.mlappinstall file) in the "build" directory.

**********
Contribute
**********

*SetupSkyLOSA* is intended be a research tool that improves over time - your input to introduce and improve functionality would be highly appreciated. Consider contributing in the following ways:

  1. Have a bug report? Raise an issue on github.

  2. Want to introduce functionality helpful to your work? Fork the repository, make it work for you, and issue a pull request. Credit will always be given.

.. _AnchorToLicense:

*******
License
*******

*SetupSkyLOSA* is licensed under the **MIT** license:

  .. include:: ../LICENSE.txt

Colourmap
=========

.. include:: ../README.rst
  :start-after: colourmap-start
  :end-before: colourmap-end

**************************
Author Contact Information
**************************

You can contact Bradley (Brad) Conrad with issues and/or recommendations at brad.conrad@carleton.ca or brad.m.conrad@gmail.com

***************
Version History
***************

.. include:: ../README.rst
  :start-after: version-start
  :end-before: version-end

****************
Acknowledgements
****************

*SetupSkyLOSA* was developed at Carleton University's `Energy and Emissions Research Laboratory <http://www.carleton.ca/eerl>`_ with support from `NSERC FlareNet <http://www.flarenet.ca>`_ and Natural Resources Canada.

.. image:: images/Logo_EERL.png
   :scale: 40 %
   :align: center
   :target: http://www.carleton.ca/eerl

|

.. image:: images/Logo_FlareNet.png
   :scale: 40 %
   :align: center
   :target: http://www.flarenet.ca
