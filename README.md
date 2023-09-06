# Image_Colorization

This project is an implementation of the image colorization algorithm from the [Deep Koalarization: Image Colorization using CNNs and Inception-Resnet-v2](https://arxiv.org/pdf/1712.03400.pdf) paper by Federico Baldassarre, Diego Gonzalez Morin∗∗, Lucas Rodés-Guirao.

<div style="display: flex; justify-content: space-between;">
  <img src="images/image1.jpg" alt="Image 1" width="30%">
  <img src="images/image2.jpg" alt="Image 2" width="30%">
</div>

The algorithm consists of an Autoencoder trained from scratch and connected in parallel to a pre-trained Inception-ResNet-v2 model.

Training data link: https://www.kaggle.com/code/theblackmamba31/autoencoder-grayscale-to-color-image/input
Inception-ResNet-v2 model weights link: https://www.kaggle.com/code/valkling/image-colorization-using-autoencoders-and-resnet/input
