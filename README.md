# MDA-HSI - Multi-Dimensional Deep Hierarchical Approach Towards Aerial Hyperspectral Image Classification

## Description 

This paper proposes MDA-HSI, a dual model integrated voting network for hyperspectral image classification. The first model employs a 3D-2D hierarchical structure to provide the spectral spatial joint features along with the abstract level spatial representation of 2D CNNs. The second model is a 3D CNN where the performance increase is provided by incorporating overlapping patches on the original hyperspectral cube to create feature maps over multiple contiguous bands.

## Datasets

## Prerequisites

- [Tensorflow](https://github.com/tensorflow/tensorflow)
- [Keras 2.0](https://github.com/fchollet/keras)
- [Spectral](https://github.com/spectralpython/spectral)
- [OpenCV-Python](https://github.com/opencv/opencv)

## Model Architecture

## Results

## Metrics

Model 1                                                          Model 2                                       Ensemble

<img src="metrics/IP/IP_CM1.JPG" width="275" height="275"/> <img src="metrics/IP/IP_CM2.JPG" width="275" height="275"/> <img src="metrics/IP/IP_CM_ENSEMBLE.JPG" width="275" height="275"/>


<img src="metrics/SA/SA_CM1.JPG" width="275" height="275"/> <img src="metrics/SA/SA_CM2.JPG" width="275" height="275"/> <img src="metrics/SA/SA_CM_ENSEMBLE.JPG" width="275" height="275"/>


<img src="metrics/PU/PU_CM1.JPG" width="275" height="275"/> <img src="metrics/PU/PU_CM2.JPG" width="275" height="275"/> <img src="metrics/PU/PU_CM_ENSEMBLE.JPG" width="275" height="275"/>
