### mars_v2

The `mars_v2` file shows an approach where smaller images are padded to Full HD resolution. This method didn't work well, as it led to worse results and required much more computational power to train.

### mars_v3

The `mars_v3` file presents a better solution, where the decoder part of the network was changed. Instead of using transposed convolution, interpolation is now used, so the network can handle images of different sizes.
