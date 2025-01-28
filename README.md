# Project Description

## mars_v2

The `mars_v2` file demonstrates an approach where smaller images are padded to Full HD resolution. Unfortunately, this method did not yield good results as it led to worse performance and required significantly more computational power during training.

## mars_v3

The `mars_v3` file presents an improved solution. In this version, the decoder part of the network was modified. Instead of using transposed convolutions, interpolation is now applied, allowing the network to handle images of various sizes more effectively.

## Datasets

- **Real Images (512x512)**: [MarsData](https://github.com/CVIR-Lab/MarsData)
- **Synthetic Images (1920x1080)**: [SynMars](https://github.com/CVIR-Lab/SynMars/tree/master)
