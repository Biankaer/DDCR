# DDCRNet

Official repository for the paper:

**Dual-Domain Consistent Reconstruction for Low-False-Alarm Hyperspectral Anomaly Detection**

This repository will host the implementation of DDCRNet, a dual-domain consistent reconstruction network for unsupervised hyperspectral anomaly detection.

## Overview

Hyperspectral anomaly detection aims to identify spectrally unusual targets without using anomaly labels during training. Reconstruction-based methods are effective for this unsupervised setting, but they may suffer from a reconstruction selectivity dilemma: insufficient reconstruction can leave complex background structures as false alarms, while overly faithful reconstruction may absorb small anomalous responses.

DDCRNet addresses this issue by combining spatial and frequency reconstruction biases:

- A spatial Mamba-HGRF branch captures long-range background context while preserving local spatial structures.
- An FFT-based real-imaginary branch introduces spatial-frequency reconstruction consistency for background suppression.
- A frequency-amplitude consistency loss constrains reconstruction toward background-dominated frequency statistics.

## Code Availability

The source code, training scripts, inference scripts, and detailed usage instructions will be released after the paper is accepted.

At the current submission stage, this repository is used as a placeholder for the official implementation.

## Citation

The BibTeX citation will be added after publication.

## Contact

For questions about the paper or future code release, please contact the corresponding author listed in the manuscript.
