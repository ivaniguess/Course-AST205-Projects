# Stellar Photometry and Optimal Aperture

This project analyzes stellar photometry using SDSS images in the **g** and **r** bands. The goal is to determine the optimal aperture radius by maximizing the signal-to-noise ratio (S/N) and to characterize stars through a color–magnitude diagram.

## Method

- Aperture photometry performed with **APT**
- S/N evaluated for radii from 1–15 pixels
- Optimal aperture selected at maximum S/N
- Radial profiles used to estimate **FWHM**
- Magnitudes calibrated using SDSS zeropoint
- Distances derived from parallax
- Absolute magnitudes and luminosities computed

## Results

- S/N curves show a clear maximum defining the optimal aperture  
- Optimal radii are consistent with the PSF scale (FWHM)  
- Background follows a Gaussian distribution  
- The color–magnitude diagram separates:
  - a **main-sequence star**
  - a **white dwarf**, fainter and bluer  

## Files

- `APT_project_real.ipynb` → photometry & S/N  
- `HR_diagram.ipynb` → color–magnitude diagram  
- `3D.ipynb` → PSF visualization  
- `hr_data.csv` → stellar data  

## Requirements

Python, numpy, matplotlib, astropy, pandas, APT
