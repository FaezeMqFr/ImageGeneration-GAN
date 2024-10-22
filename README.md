## Dataset Information

### MNIST

The MNIST dataset contains 60,000 training examples and 10,000 testing examples of 28x28 grayscale images of handwritten digits (0-9). In `GANs_MNIST.ipynb`, the GAN is trained to generate synthetic images that resemble handwritten digits.

### CIFAR-10

The CIFAR-10 dataset contains 60,000 32x32 color images across 10 different classes, with 50,000 images for training and 10,000 for testing. In `GANs_CIFAR-10.ipynb`, the GAN is trained to generate synthetic images that resemble the CIFAR-10 dataset categories (e.g., animals, vehicles).

## Structure of the GAN

Each notebook follows the standard structure of a GAN:

1. **Generator**: A neural network that takes random noise as input and generates images.
2. **Discriminator**: A neural network that classifies images as real or fake.
3. **Training Loop**: Alternates between training the discriminator and the generator to improve the generator’s ability to produce realistic images.

## Running the Notebooks

To train the GAN models, follow these steps:

1. Open the notebooks in JupyterLab or Jupyter Notebook.
2. Run the cells to import necessary libraries and load the dataset.
3. Execute the training loop, which will iteratively update the generator and discriminator models.
4. Monitor the generated images during training to observe the improvements in the generator’s output over time.

## Results and Visualization

During training, the generated images are saved or displayed to monitor the quality of the GAN. The notebooks visualize the progress of generated images over multiple epochs, allowing you to observe how well the GAN learns to replicate the dataset images.

## Customization

You can customize the GAN architecture by modifying the generator and discriminator models in the notebooks. Additionally, hyperparameters such as learning rate, batch size, and number of epochs can be tuned to improve performance.

## References

- Ian Goodfellow et al., “Generative Adversarial Nets,” Advances in Neural Information Processing Systems, 2014.
- The original MNIST dataset: [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)
- The CIFAR-10 dataset: [https://www.cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html)

## License

This project is open-source and licensed under the MIT License.
