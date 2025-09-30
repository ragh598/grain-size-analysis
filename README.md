# Automated Grain Size Analysis Using SAM

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)]()

Raw Image:
<img width="2560" height="1920" alt="image" src="https://github.com/user-attachments/assets/95b9da5e-ed01-48bc-8ec1-1d0e16d359a8" />
Model output:
<img width="2521" height="1922" alt="image0001_with_areas" src="https://github.com/user-attachments/assets/44a9e200-f492-495b-a18c-7a221d6b1d04" />

> High-throughput automated grain size analysis for materials science using Meta's Segment Anything Model (SAM)
> **Performance:** Analyzed 10,830+ grains across multiple duralumin samples
- Mean grain area: 916.4 μm²
- Processing speed: 12 images/hous on GPU T4 on Google Colab
- This was implemented with sequential image input to the model. This code can be further optimized for multi-processing.
- **~90% reduction** in analysis time vs. manual methods
