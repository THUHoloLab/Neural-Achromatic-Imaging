# Neural Achromatic Imaging for Large-Scale Metalens

Official repository for the paper:

**Neural achromatic imaging for large-scale metalens**  
Jinwen Wei, Yunhui Gao, and Liangcai Cao*

## Overview

This project presents a neural achromatic imaging framework for large-scale metalens imaging.  
The method addresses severe chromatic aberration in full-color metalens imaging by combining:

- cross-channel image prior
- physics-informed forward imaging model
- PSF-aware Meta-Achromatic Network

The proposed framework exploits cross-channel correlations in RGB images and introduces PSF-aware attention to improve achromatic reconstruction quality for large-scale diffractive imaging systems.

## Main Results

On the 7-mm-aperture metalens prototype reported in the paper, the proposed method achieves:

- **51% reduction** in the introduced chromatic aberration metric
- **10.19 dB PSNR improvement** over raw captured images
- preserved recovery performance in low-light imaging

## Repository Status

This repository is currently being prepared.

- To be released after paper acceptance
- core training and inference code
- model architecture implementation
- data processing scripts
