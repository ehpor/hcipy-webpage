---
title: "About"
---

## What is HCIPy?

HCIPy is an open-source, modular Python package for high-contrast imaging on current and future telescopes. By integrating atmospheric simulation, wavefront sensors and coronagraphs in a single library, HCIPy enables both rapid prototyping of individual system elements and the full high-contrast imaging system.

The library defines wavefronts and optical elements for defining an optical system, and provides both Fraunhofer and Fresnel diffraction propagators. Polarization is supported using Jones calculus, with polarizers and waveplates included out of the box. It implements atmospheric turbulence using thin infinitely-long phase screens, and can model scintillation using Fresnel propagation between individual layers. Many wavefront sensors are implemented including a Shack-Hartmann and Pyramid wavefront sensor. Implemented coronagraphs include the vortex, Lyot and APP coronagraph.

By including simulation of both adaptive optics and coronagraphy into a single framework, HCIPy allows simulations including feedback from post-coronagraphic focal-plane wavefront sensors to the AO system.

## Acknowledging

If you use HCIPy for your own research, we ask you to cite the HCIPy proceeding ([Por et al. 2018](https://ui.adsabs.harvard.edu/abs/2018SPIE10703E..42P)). If there is no appropriate place in the body text to cite the proceeding, please include something along the lines of the following in your acknowledgements:

> This research made use of HCIPy, an open-source object-oriented framework written in Python for performing end-to-end simulations of high-contrast imaging instruments ([Por et al. 2018](https://ui.adsabs.harvard.edu/abs/2018SPIE10703E..42P)).

## Contributing

Development takes place on [Github](http://github.com/ehpor/hcipy). We welcome external contributions to HCIPy, be it small or large. If you have something to add, or want something added to HCIPy, please let us know with a [Github issue](http://github.com/ehpor/hcipy/issues).

## Publications

This is a, likely incomplete, list of publications which use HCIPy:

- [Maier et al. 2020](https://doi.org/10.1117/12.2560878), "Design of the vacuum high contrast imaging testbed for CDEEP, the Coronagraphic Debris and Exoplanet Exploring Pioneer", Proc. SPIE 11443
- [Laginja et al. 2020](https://doi.org/10.1117/12.2560113), "Predicting contrast sensitivity to segmented aperture misalignment modes for the HiCAT testbed", Proc. SPIE 11443
- [Por et al. 2020](https://doi.org/10.1117/12.2562571), "Exploiting symmetries and progressive refinement for apodized pupil Lyot coronagraph design", Proc. SPIE 11443
- [Wang et al. 2020](https://doi.org/10.1117/12.2559345), "Finding exoplanets in the habitable zone with light echoes", Proc. SPIE 11448
- [Bos et al. 2020](https://doi.org/10.1117/12.2562183), "New concepts in vector-apodizing phase plate coronagraphy", Proc. SPIE 11448
- [Haffert et al. 2020](https://doi.org/10.1117/12.2562610), "Using the generalised-optical differentiation wavefront sensor for laser guide star wavefront sensing", Proc. SPIE 11448
- [Dodkins et al. 2020](https://doi.org/10.1088/1538-3873/aba9e4), "First Principle Simulator of a Stochastically Varying Image Plane for Photon-Counting High Contrast Applications", PASP 132:104503
- [Bos et al. 2020](https://doi.org/10.1051/0004-6361/202037910), "On-sky verification of Fast and Furious focal-plane wavefront sensing: Moving forward toward controlling the island effect at Subaru/SCExAO", A&A 639, A52
- [Landman et al. 2020](https://doi.org/10.1364/OE.389465), "Nonlinear wavefront reconstruction with convolutional neural networks for Fourier-based wavefront sensors", Optics Express 28.11, 16644-16657
- [Bos 2020](https://doi.org/10.1051/0004-6361/202037957), "Vector speckle grid: instantaneous incoherent speckle grid for high-precision astrometry and photometry in high-contrast imaging", A&A 638, A118
- [Doelman et al. 2020](https://doi.org/10.1088/1538-3873/ab755f), "Minimizing the Polarization Leakage of Geometric-phase Coronagraphs with Multiple Grating Pattern Combinations", PASP 132:045002
- [Por 2020](https://doi.org/10.3847/1538-4357/ab3857), "Phase-apodized-pupil Lyot Coronagraphs for Arbitrary Telescope Pupils", ApJ 888, 127
- [Bos et al. 2019](https://doi.org/10.1051/0004-6361/201936062), "Focal-plane wavefront sensing with the vector-Apodizing Phase Plate", A&A 632, A48
- [Van Kooten et al. 2019](https://doi.org/10.1364/JOSAA.36.000731), "Impact of time-variant turbulence behavior on prediction for adaptive optics systems", JOSA A 36, 731-740
- [Doelman et al. 2019](https://doi.org/10.1364/OME.9.001246), "Multi-color holography with a two-stage patterned liquid-crystal element", Optical Materials Express 9, 1246-1256
- [Doelman et al. 2019](https://doi.org/10.1364/OL.44.000017), "Simultaneous phase and amplitude aberration sensing with a liquid-crystal vector-Zernike phase mask", Optics Letters 44.1, 17-20
- [Jensen-Clem et al. 2019](https://doi.org/10.1117/12.2529687), "Demonstrating predictive wavefront control with the Keck II near-infrared pyramid wavefront sensor", Proc. SPIE 11117
- [Laginja et al. 2019](https://doi.org/10.1117/12.2530300), "Wavefront error tolerancing for direct imaging of exo-Earths with a large segmented telescope in space", Proc. SPIE 11117
- [Cantalloube et al. 2018](https://doi.org/10.1051/0004-6361/201834311), "Origin of the asymmetry of the wind driven halo observed in high-contrast images", A&A 620, L10
- [Bos et al. 2018](https://doi.org/10.1117/12.2312798), "Fully broadband vAPP coronagraphs enabling polarimetric high contrast imaging", Proc. SPIE 10706
- [Radhakrishnan et al. 2018](https://doi.org/10.1117/12.2312290), "Optimization of contrast in adaptive optics for exoplanet imaging", Proc. SPIE 10703
- [Por et al. 2018](https://doi.org/10.1117/12.2314407), "High Contrast Imaging for Python (HCIPy): an open-source adaptive optics and coronagraph simulator", Proc. SPIE 10703
