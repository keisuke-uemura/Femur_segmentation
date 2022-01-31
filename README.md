# Femur_segmentation

This model segments the bilateral femur from CT images.
The segmentation model was built from convolutional neural network using a Bayesian U-net architecture (https://github.com/yuta-hi/bayesian_unet) and was trained on manual segmentations of 120 cases.

# Requirements
- Python 3.6
- keras 2.2.3
- CPU or NVIDIA GPU + CUDA CuDNN

Tested on the following environments:
Win10, GPU: GTX1080 CUDA: 10.1, CuDNN: 7.6.5

For details, please see [requirements.txt](requirements.txt)

# Licence
Codes can be used for research purpose or for educational purpose.

For details, please see LICENCE.txt
