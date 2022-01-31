# Femur_segmentation

This model segments the bilateral femur from CT images.
The segmentation model was built from convolutional neural network using a Bayesian U-net architecture (https://github.com/yuta-hi/bayesian_unet) and was trained on manual segmentations of 120 cases.

## Reference
Journal paper can be found at (https://doi.org/10.1007/s11657-022-01063-3)

When using these codes, please cite

- Uemura, K., Otake, Y., Takao, M. et al. Development of an open-source measurement system to assess the areal bone mineral density of the proximal femur from clinical CT images. Arch Osteoporos.(2022). https://doi.org/10.1007/s11657-022-01063-3

# Requirements
- Python 3.6
- keras 2.2.3
- CPU or NVIDIA GPU + CUDA CuDNN

Tested on the following environments:
Win10, GPU: GTX1080 CUDA: 10.1, CuDNN: 7.6.5

For details, please see [requirements.txt](requirements.txt)

# Licence
Codes can be used for research purpose or for educational purpose.

For details, please see [LICENCE.txt](LICENCE.txt)
