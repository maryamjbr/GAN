# Generative Adversarial Network (GAN) for MNIST Digits
This project implements a Generative Adversarial Network (GAN) to generate MNIST digit images using PyTorch. The GAN consists of a Generator and a Discriminator, which are trained adversarially: the Generator tries to create realistic images, while the Discriminator attempts to distinguish between real and fake images.
## Project Details
The notebook performs the following steps:

- Data Loading and Preprocessing: Loads the MNIST dataset and preprocesses it by padding and normalizing the images.
- Visualization Function: Defines a function to visualize the images.
- Model Definition: Defines the Generator and Discriminator classes using convolutional and transposed convolutional layers.
- Training: Trains the GAN on the MNIST training data for a specified number of epochs, minimizing the Binary Cross-Entropy (BCE) loss.
- Visualization: Visualizes the generated images during and after training.
## Results
The results of the GAN training, including the generated images at different epochs, are visualized and printed in the notebook.

## Example Output
![GAN](https://github.com/maryamjbr/GAN/assets/135154626/f1f33087-343d-4337-abe0-af14aca2fd66)


