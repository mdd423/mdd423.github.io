---
title: "Jabble: Data-Driven Radial Velocity Pipeline" 
date: 2026-02-16
tags: ["astrophysics","exoplanets","data science"]
author: ["Matthew Daunt"]
description: "This project measures stellar radial velocities from high resolution echelle spectra."
summary: "This project measures stellar radial velocities from high resolution echelle spectra."
cover:
    image: "spectra_51peg_o66-67_l6555.0-6567.0_.png"
    alt: "Models of stellar and telluric spectra"
    relative: true
editPost:
    URL: "https://github.com/mdd423/wobble_jax"
    Text: "Github"
showToc: false
disableAnchoredHeadings: false

---

---

#### Abstract from Thesis

In this chapter, we deliver a data-driven method to fitting a static stellar template, and Doppler shifts (RVs), to a multi-epoch spectroscopic campaign. We use a spline-like model for the stellar spectrum, another spline-like model for the telluric absorption, and a much lower-resolution model for pseudo-continuum normalization. With the construction of new spectrographs like NEID, and substantial archives from  spectrographs like HARPS and Keck HIRES, there are abundant high signal-to-noise, multi-epoch spectral campaigns of relevance. Small improvements in data analysis can leverage improvements in hardware, which are continually being advanced. Here we implement a statistical (frequentist) method that delivers appropriately co-added spectral data and maximum-likelihood RVs to optimally extract RV information from the spectra. This method takes as input un-normalized (or poorly normalized) heteroskedastic one-dimensional spectral data, even on heterogeneous wavelength grids, and outputs precise relative RVs at all epochs, and a high signal-to-noise tellurics-free mean spectrum.

---

#### View

+ [Poster for ERES IX](Jabble_Poster_for_ERES_IX-3.pdf)

---
