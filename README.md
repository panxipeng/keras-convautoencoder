# Keras autoencoders (convolutional/fcc) [proof of concept]
This is an implementation of weight-tieing layers that can be used to consturct convolutional autoencoder and 
simple fully connected autoencoder. It might feel be a bit hacky towards, however it does the job.

## Convolutional autoencoder example

Run conv_autoencoder.py.
 
## FCC autoencoder example

Run conv_autoencoder.py.
Conv layer (32 kern of 3x3) -> MaxPool (2x2) -> Dense (10) -> UpSample (2x2) -> DeConv layer (32 kern of 3x3)
![ConvAutoEncoder MNIST representations](./img/cc.png "ConvAutoEncoder MNIST representations")

## FCC autoencoder example

Run fcc_autoencoder.py.
Conv layer (32 kern of 3x3) -> MaxPool (2x2) -> Dense (10) -> UpSample (2x2) -> DeConv layer (32 kern of 3x3)
![ConvAutoEncoder MNIST representations](./img/fcc.png "ConvAutoEncoder MNIST representations")