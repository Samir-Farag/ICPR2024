# ICPR2024
This repository contains the implementation code for model architecture for our paper recently accepted at the ICPR 2024 conference. For more information about coding, please contact: safara01@louisville.edu
 
## The paper: "Colon Segmentation Using Guided Sequential Episodic Training and Contrastive Learning"

More contents will be added later.

AAS-DCL.zip: Includes all codes utilized in training and validating the baseline AAS-DCL, and the architicture is adopted from the official implementation here: https://github.com/cvszusparkle/AAS-DCL_FSS.

Guided_SET_DCL.zip: Includes all codes employed in training and validating the Guided-SET-DCL approach based on the official implementation of the baseline AAS-DCL.

SSL-ALPNet.zip: This folder includes all codes included in training and validating the SSL-ALPNet approach based on the official implementation at https://github.com/cheng-01037/Self-supervised-Fewshot-Medical-Image-Segmentation.

final_MRF.zip: Includes all codes included in the implementation of the MRF initial labeling algorithm used for guiding the proposed Guided-SET_DCL. You have to generate initial labeling for the dataset before applying codes in Guided_SET_DCL.zip.



Requirements

### CUDA/CUDNN torch >= 1.4.0 torchvision numpy

### Datasets 
 
To get access for our private dataset, please contact aly.farag@louisville.edu
Public dataset is available at: https://www.synapse.org/Synapse:syn3193805/wiki/217789
