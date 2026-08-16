# STARTastro Na I D Research

Undergraduate astronomy research project completed through the University of California San Diego (UCSD) Summer Research Program (SRP) with the specific program STARTastro at UCSD and San Diego State University (SDSU)

## Project Overview

This project explores Na I D absorption in the model spectra of elliptical galaxies and how changes in alpha-element abundance, [⍺/Fe], affect the observed absorption features.

The analysis focused on continuum normalization, modeling the Na I D doublet with Gaussian absorption profiles, and comparing the fitted models across multiple [⍺/Fe] values.

## Methods

- Converted wavelengths from air to vacuum
- Selected the Na I D spectral region
- Fit the local continuum using the Legendre polynomial
- Continuum-normalized the spectrum
- Modeled the Na I D doublet using Gaussian absorption profiles
- Optimized model parameters using `scipy.optimize.curve_fit`
- Compared the normalized spectra and fitted models
- Examined residual absorption using spectrum-to-model ratios

## Tools

- Python
- NumPy
- Matplotlib
- SciPy
- Astropy
- Specutils
- Jupyter Notebooks
- VS Code

## Repository Structure

- 'Notebooks/' - Jupyter notebooks containing the analysis
- 'Figures/' - selected figures from the final analysis

## Research Context

Na I D absorption can be used when studying gas flows in elliptical galaxies, but stellar absorption can contribute to the observed signal. This project examines the stellar Na I D contribution in model spectra to better understand how it may affect interpretations of gas inflow or outflow.

## Author

- Daniel Quezada Jimenez
-B.S. Astronomy Student, San Diego State University
- Mathematics Minor
