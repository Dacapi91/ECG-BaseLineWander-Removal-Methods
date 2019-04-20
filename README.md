# BaseLineWander Removal Methods

<img src="https://github.com/fperdigon/ECG-BaseLineWander-Removal-Methods/blob/master/ecg_image.png" width="300">

This repository contains the implementation of several baseline wander removals methods for ECG signals. Also contains the implementation of similarity metrics and some utils funtions for ECG precessing.

All these functions were implemented in MATLAB.

All these methods were programmed according the literature information.
The reference to these papers appear in the header information of each method.

## Files description:

BLremover.m (9 methods for Base Line Wander removal)
- Based on Cubic SPlines
- Based on FIR filters
- Based on IRR filters
- Based on LMS adaptive filters
- Based on moving-average filter
- Based on Independent Components Analysis (ICA)
- Based on Interpolation and Successive Subtraction of Median Values (ISSM)
- Based on Empirical Mode Decomposition (EMD)
- Based on Wavelet Transform

SimMetricsECG.m (3 similarity metrics)
- Maximum Absolute Distance Metric (MAD)
- Sum Square Distance Metric (SSD)
- Percentage Root-Mean-Square Difference Metric (PRD)

utilECG.m (Several ECG tools)
- Methods to detect R peaks
- Methods to detect PQ intervals
- Methods for filtering the ECG signal
- Methods to add artificial noise (BLW, power line)

## References

- F. P. Romero, L. V. Romaguera, C. R. Vázquez-Seisdedos, C. F. F. C. Filho, M. G. F. Costa, and J. E. Neto, “Baseline wander removal methods for ECG signals: A comparative study,” Jul. 2018.

## Citing this work

When citing this work please use this BibTeX entry:

@article{Romero2018,
title = {{Baseline wander removal methods for ECG signals: A comparative study}},
archivePrefix = {arXiv},
arxivId = {1807.11359},
author = {Romero, Francisco Perdig{\'{o}}n and Romaguera, Liset V{\'{a}}zquez and V{\'{a}}zquez-Seisdedos, Carlos Rom{\'{a}}n and Filho, C{\'{i}}cero Ferreira Fernandes Costa and Costa, Marly Guimar{\~{a}}es Fernandes and Neto, Jo{\~{a}}o Evangelista},
eprint = {1807.11359},
month = {jul},
url = {http://arxiv.org/abs/1807.11359},
year = {2018}
}

 
MIT License

Copyright (c) 2018 Francisco Perdigon Romero
