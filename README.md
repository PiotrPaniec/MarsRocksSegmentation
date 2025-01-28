File mars_v2 shows an approach where smaller images are padded to FullHD resolution. It was not the best idea, because of much worse results and it needed much more omputational power to train.

File mars_v3 shows a better idea, where the decoder part of network was changed (interpolation instead of transposed convolution), so now the network can handle images with different sizes.
