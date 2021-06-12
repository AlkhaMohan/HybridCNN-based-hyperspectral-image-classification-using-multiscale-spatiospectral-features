# HybridCNN based hyperspectral image classification using multiscale spatiospectral features
# Python Implementation for HybridCNN
## Abstract
Hyperspectral images (HSIs) are contiguous band images widely used in remote sensing applications. The evolution of deep learning techniques made a significant impact on HSI classification. Several HSI processing applications rely on various Convolutional Neural Network (CNN) models. However, the higher dimensionality nature of HSIs increases the computational complexity and leads to the Hughes phenomenon. Therefore most of the CNN models perform dimensionality reduction (DR) as a preprocessing step. Another challenge in HSI classification is the consideration of both spatial and spectral features for obtaining accurate results. A few 3-D-CNN models are designed to overcome this challenge, but it takes more execution time than other methods. This research work proposes a multiscale spatio-spectral feature based hybrid CNN model for hyperspectral image classification. Hybrid DR used for optimal band extraction, which performs linear Gaussian Random Projection (GRP) and non-linear Kernel Principal Component Analysis (KPCA). The proposed hybrid CNN classification technique extracts the spectral and spatial features for different window sizes using 3D-CNN. These features concatenated and fed into a 2D-CNN for further feature extraction and classification. The hybrid model is compared against various state-of-the-art CNN based techniques and found to showcase a satisfactory result with less computational complexity.
## Proposed Model
![Model_img](https://user-images.githubusercontent.com/35597958/121773944-e8712d00-cb9c-11eb-98df-9d85e1a0f9a6.PNG)
## Citation
### If you use HybridCNN code for your research works, we would appreciate a citation to the original paper
```
@article{MOHAN2020103326,
title = {HybridCNN based hyperspectral image classification using multiscale spatiospectral features},
journal = {Infrared Physics & Technology},
volume = {108},
pages = {103326},
year = {2020},
issn = {1350-4495},
doi = {https://doi.org/10.1016/j.infrared.2020.103326},
url = {https://www.sciencedirect.com/science/article/pii/S1350449519310485},
author = {Alkha Mohan and M Venkatesan},
}
```
