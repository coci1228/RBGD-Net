# RBGD-Net

**RBGD-Net: Region-Boundary Guided and Gated Decoding Network for Farmland Parcel Extraction from Remote Sensing Imagery**

> **Code release pending.** The source code and implementation details will be made publicly available in this repository upon acceptance of the paper.

## Overview

RBGD-Net is a framework for binary farmland segmentation in high-resolution remote sensing imagery. It combines a frozen DINOv3 encoder with spatial feature adaptation, region-boundary refinement, and gated multi-scale contextual modeling.

The framework includes three main components:

- **Semantic Deformable Adapter (SD-Adapter):** Integrates convolutional spatial priors with frozen DINOv3 features. A Semantic Reliability Gate (SRG) regulates semantic fusion using cosine consistency.
- **Decoupled Region-Boundary Attention Module (DRBAM):** Processes regional and boundary-oriented information through separate feature pathways, with boundary-guided adaptive sampling and gated fusion.
- **Gated Dual-Path Multi-scale Projection Module (GDPM):** Combines a shortcut projection with local-to-global contextual refinement before decoding.

## Datasets

The manuscript evaluates RBGD-Net on three farmland datasets:

- iFLYTEK Farmland Parcel Extraction Challenge dataset
- First Large-Scale Very-High-Resolution Agricultural Parcel Dataset (FHAPD)
- Chinese Cropland Parcel Dataset (CCPD)

The task is binary semantic segmentation, with evaluation following the annotation conventions of each dataset.

## Code Availability

This repository currently serves as the project page. The implementation has not yet been released.

The source code and implementation details will be released upon acceptance of the paper. Installation instructions and training and evaluation documentation will accompany the code release.

## Citation

Publication details and citation information will be added after the paper is accepted.
