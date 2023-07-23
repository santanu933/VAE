# VAE
# Variational Autoencoders with Frey Face Dataset

This repository contains code for training variational autoencoders (VAEs) using the Frey Face dataset and generating samples from the learned distribution. The code is implemented in Python using the Keras library.

## Dataset

The Frey Face dataset is available for download from the following link: [Frey Face Dataset](https://cs.nyu.edu/~roweis/data/frey_rawface.mat)

1. Please download the dataset and place it in the `data` directory.


2. Navigate to the project directory:


3. Create a virtual environment (optional but recommended):


4. Install the required dependencies:

## Libraries Used

The code relies on the following Python libraries:

- Keras
- NumPy
- Matplotlib
- SciPy


## Training

1. Run the training script to train the VAE:

 configure the training process by modifying the parameters in the `config.py` file. Some of the important parameters include:

- `latent_dim`: The size of the latent space. (Default: 20)
- `batch_size`: The batch size for training the VAE. (Default: 128)
- `epochs`: The number of epochs to train the VAE. (Default: 50)
- `learning_rate`: The learning rate for the optimizer. (Default: 0.001)

2. The trained model will be saved in the `models` directory.

## Generating Samples

1. Run the sampling script to generate samples from the learned distribution:


2. The generated samples will be displayed.

## Configuration

You can modify the configuration settings in the `config.py` file to adjust the hyperparameters and other options for training the VAE.

## Additional Notes

- You can modify the architecture of the VAE model by editing the `create_vae_model()` function in `vae.py`.
- For more details about the VAE architecture and implementation, refer to the code comments and the provided references.
- 
## License

This project is licensed under the MIT License. See the LICENSE file for details.

