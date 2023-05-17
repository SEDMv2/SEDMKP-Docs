.. SED Machine documentation master file, created by
   sphinx-quickstart on Sun Jun  7 12:15:18 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SED Machine Kitt Peak's documentation!
=================================================

SED Machine Kitt Peak is very low resolution (:math:`\frac{\lambda}{\Delta
\lambda}\sim100`) optical (365 - 1,000 nm) integral field (28"x"28")
spectrograph and an imager with a 6' x 6' field.  The instrument was 
designed for rapid classification of supernovae from transient surveys and
is based on the original `SEDM`_ on the Palomar 60-inch telescope.

.. _SEDM: http://www.astro.caltech.edu/sedm

To achieve this goal, the instrument was designed to have:

- Low resolution (:math:`R=\frac{\lambda}{\Delta \lambda}\sim100`), sufficient for classification.
- High "Slit to detector" photon throughput.
- 0.1 mag precision spectrophotometry.

The project is funded by a consortium of private foundations and public
institutions.  The partners who will share time on SEDM KP are:

- Caltech
- University of Minnesota
- JSI, Goddard/University of Maryland
- Northwestern University
- Space Telescope Science Institute

If you use SEDM data please use the following text in your published papers:

Based on observations obtained with the Spectral Energy Distribution Machine on
the Kitt Peak 2.1-m telescope (SEDM-KP). The SEDM-KP team thanks the National
Science Foundation and the National Optical-Infrared Astronomy Research
Laboratory for making the Kitt Peak 2.1-m telescope available. SEDM-KP is
supported by the Heising Simons Foundation under Grant No. 2021-2612, titled
"The SEDM Kitt Peak Project," and a collaboration including current partners
Caltech, University of Minnesota, the University of Maryland/NASA-Goddard,
Northwestern University, and the Space Telescope Science Institute.

If you use IFU data please cite: `Rigault, Neill, Walters, et al. 2019, A&A, 627, A115 <https://ui.adsabs.harvard.edu/abs/2019A%26A...627A.115R/abstract>`_.

Many people were involved.  A partial list of current members of the team are:

- Don Neill (Instrument Scientist, IFU pipeline automation, Caltech)
- Mickael Rigault (IFU pipeline lead developer, CNRS/IN2P3, France)
- Yashvi Sharma (Science operations, DRP, Caltech)
- Reed Riddle (SEDM-KP software/operations, Caltech)
- Josiah Purdum (Operations, Caltech)
- Michael Coughlin (Project Scientist, UMinn)

Here we document the instrument for observers and developers.  Observers
will want to refer to the Observer's Reference below.

Data products produced by the automatic pipeline can be found `here`_ (a
login account is required).

.. _here: http://minar.caltech.edu/data_access/ifu


Contents:

.. toctree::
    :numbered:
    :maxdepth: 2

    Introduction
    Team
    ObsRef
    Pipeline
    Timeline
    Hardware

Last updated on |version|
