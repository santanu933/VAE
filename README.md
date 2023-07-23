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


2. The trained model will be saved in the `models` directory.

## Generating Samples

1. Run the sampling script to generate samples from the learned distribution:


2. The generated samples will be displayed.

## Configuration

You can modify the configuration settings in the `config.py` file to adjust the hyperparameters and other options for training the VAE.


## License

This project is licensed under the MIT License. See the LICENSE file for details.

