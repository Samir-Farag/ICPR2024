# ICPR2024
This repository contains the implementation code for the model architecture presented in our paper recently accepted at the ICPR 2024 conference. For more information about the code, please contact: safara01@louisville.edu.

## The Paper: "Colon Segmentation Using Guided Sequential Episodic Training and Contrastive Learning"
More content will be added later.

## Standard FSS Models

### 1. AAS-DCL
We have provided the code utilized in training and validating the baseline AAS-DCL model. The architecture is adopted from the official implementation [here](https://github.com/cvszusparkle/AAS-DCL_FSS).

### 2. SSL-ALPNet
All code for training and validating the SSL-ALPNet approach is included, based on the official implementation available [here](https://github.com/cheng-01037/Self-supervised-Fewshot-Medical-Image-Segmentation).

## Proposed Models

### 1. Guided_SET_DCL.zip
This includes all the code used for training and validating the Guided-SET-DCL approach, based on the official implementation of the baseline AAS-DCL.

### 2. final_MRF.zip
This includes all the code used in the implementation of the MRF initial labeling algorithm, which is used for guiding the proposed Guided-SET_DCL. You need to generate initial labeling for the dataset before applying the code in Guided_SET_DCL.zip.

## Requirements

- CUDA/CUDNN
- torch >= 1.4.0
- torchvision
- numpy

## Datasets

To get access to our private dataset, please contact aly.farag@louisville.edu.

The public dataset is available [here](https://www.synapse.org/Synapse:syn3193805/wiki/217789).
