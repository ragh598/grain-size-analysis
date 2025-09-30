# Automated Grain Size Analysis Using SAM

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)]()

## Quick Start

### Installation
```bash
git clone https://github.com/ragh598/grain-size-analysis-sam.git
cd grain-size-analysis-sam
```
## How It Works

1. **Image Preprocessing**: Load and resize microscopy images
2. **Segmentation**: Meta's SAM generates grain masks
3. **Post-processing**: Filter, clean, and validate masks
4. **Morphometry**: Calculate area, diameter, shape factors
5. **Visualization**: Generate annotated images and plots
6. **Export**: Save results to CSV with comprehensive statistics


## Raw Image:
<img width="2560" height="1920" alt="image" src="https://github.com/user-attachments/assets/95b9da5e-ed01-48bc-8ec1-1d0e16d359a8" />

## Model output:
<img width="2521" height="1922" alt="image0001_with_areas" src="https://github.com/user-attachments/assets/44a9e200-f492-495b-a18c-7a221d6b1d04" />

> High-throughput automated grain size analysis for materials science using Meta's Segment Anything Model (SAM)
> 
> **Performance:** Analyzed 10,830+ grains across multiple duralumin samples
- Mean grain area: 916.4 μm²
- Processing speed: 12 images/hous on GPU T4 on Google Colab
- This was implemented with sequential image input to the model. This code can be further optimized for multi-processing.
- **~90% reduction** in analysis time vs. manual methods
## Why This Project?

Manual grain size analysis in materials science is:
- **Time-consuming**: Hours per sample
- **Subjective**: Skill-dependent measurements
- **Low-throughput**: Limits statistical significance

This project aims to be a cost-effective alternative to manual and tedious checks for each image to check and identify the microstructure characteristics.
This project automates the entire pipeline using SOTA Vision Transformer.

