# Image_Super_resolution

## [For h5 files click here](https://drive.google.com/drive/folders/15YH9yWSh6IjmZiWL1xh5rRtIPnEgLkPh)

Overview:

Image super resolution aims in recovering a high resolution image from a low resolution one.Our method directly learnsand end to endmapping between the high/low- resolution images. The mapping is represented as a deep Convolution Neural Network that takes the low resolution image as input and outputs a high-resolution one . We explore different network structures and parameter setting to achieve trade offs between speed and performance.

We conducted experiments from [this paper](https://arxiv.org/abs/1501.00092).

We first tested different filters. We tried the following combinations:

A.  **915**

Comparing PSNRs between Bicubic and our SRCNN for YCrCCb:







