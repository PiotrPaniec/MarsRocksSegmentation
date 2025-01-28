# Project Description

## mars_v2

The `mars_v2` file demonstrates an approach where smaller images are padded to Full HD resolution. Unfortunately, this method did not yield good results as it led to worse performance and required significantly more computational power during training.

## mars_v3

The `mars_v3` file presents an improved solution. In this version, the decoder part of the network was modified. Instead of using transposed convolutions, interpolation is now applied, allowing the network to handle images of various sizes more effectively.

Both models were trained for only 50 epochs, which is sufficient for a basic comparison. However, comparing the error curves for the training and test sets reveals that there is still significant room for improvement. After 50 epochs, the model performance is not yet optimal. A more extensive training process, lasting over 250 epochs, would be necessary to achieve better results.

## Datasets

- **Real Images (512x512)**: [MarsData](https://github.com/CVIR-Lab/MarsData)
- **Synthetic Images (1920x1080)**: [SynMars](https://github.com/CVIR-Lab/SynMars/tree/master)
