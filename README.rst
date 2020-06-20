.. image:: https://readthedocs.org/projects/skylosaacquire/badge/?version=latest
  :target: https://skylosaacquire.readthedocs.io/en/latest/?badge=latest
  :alt: Documentation Status

###################################################################
SetupSkyLOSA: A MATLAB Tool to support Acquisition of Sky-LOSA Data
###################################################################

.. abstract-start

*SetupSkyLOSA* is a MATLAB-based software tool to support an end-user in the acquisition of sky-LOSA image data used to quantify soot/black carbon emissions from gas flares.

.. abstract-end

********
Features
********

.. features-start

The accompanying submission to the `Journal of Atmospheric Measurement Techniques <https://www.atmospheric-measurement-techniques.net/index.html>`_ includes the theoretical background for *SetupSkyLOSA* and how to interpret results. The *SetupSkyLOSA* software provides guidance on the positioning and pointing of sky-LOSA camera based on statistics computed in a Monte Carlo-based General Uncertainty Analysis (GUA). The user provides the time and date, location (latitude and longitude), skylight conditions, and plume transmittance. *SetupSkyLOSA* parses these inputs and returns statistics in sky-LOSA-computed soot mass column density, which dominates sky-LOSA measurement uncertainty. The user can then interact with GUA data to determine the optimal camera pointing(s) given a desired threshold in uncertainty.

.. features-end

*************
Documentation
*************

*SetupSkyLOSA* includes complete documentation hosted by `Read the Docs <http://skylosaacquire.readthedocs.io/>`_.

*******
License
*******

This software is licensed under the `MIT <LICENSE.txt>`_ license.

Colourmap
=========

.. colourmap-start

The colourmap used in this application is adapted from the open-source **cividis** colourmap described in:

  Nuñez, J.R., Anderton, C.R., & Renslow, R.S. (2018), Optimizing colormaps with consideration for color vision deficiency to enable accurate interpretation of scientific data. **PLOS One**, 13(7):1-14 (doi: `10.1371/journal.pone.0199239 <https://doi.org/10.1371/journal.pone.0199239>`_).

.. colourmap-end

***************
Version History
***************

.. version-start

**Version 0.9**: Internal development.

.. version-end

************
Publications
************

*SetupSkyLOSA* is detailed in or referenced by the following publications:

  .. masterref-start

  Conrad, B.M. & Johnson, M.R. (2020), An uncertainty-based protocol for the measurement of soot/black carbon emissions from gas flares using sky-LOSA , **Atmos. Meas. Tech.**, *in preparation*.

  .. masterref-end

