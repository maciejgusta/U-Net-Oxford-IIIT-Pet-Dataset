# U-Net for Oxford-IIIT Pet Segmentation

**Modified U-Net implementation** based on [Ronneberger et al. (2015)](https://arxiv.org/abs/1505.04597) + training/evaluation on the Oxford-IIIT Pet Dataset (trimap segmentation).

## This repository is purely educational and aims to get insight on the U-Net architecture rather than achieve the best competetive results

## Changes to the architecture

-   “Same” instead of "valid" convolutions to preserve the input size
-   BatchNorm added to accelerate training

## Data Augmentation

-   ImageNet normalization for the input images

## Results

-   Accuracy of 89.15% on test set

![image](https://github.com/user-attachments/assets/a9c9a70d-47d1-4964-8a10-c39d770e93af)

