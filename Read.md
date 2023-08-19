# ResNet18 with Preactivation Blocks for CIFAR-10

This repository contains an implementation of a ResNet18 model with Preactivation Basic Blocks for the CIFAR-10 dataset using PyTorch. The model is trained for image classification and demonstrates the use of data augmentation, learning rate scheduling, and training validation loop setup.

## Setup and Requirements

1. Make sure you have Python 3.x and PyTorch installed.
2. Clone this repository: `git clone https://github.com/waheed047/resnet-preact-cifar10.git`
3. Install required packages: `pip install -r requirements.txt`

## Usage

1. Open a terminal and navigate to the cloned repository's directory.
2. Run the training script: `python train.py`

The script will train the ResNet18 model using CIFAR-10 dataset, showing the training and validation loss and accuracy for each epoch. After training, it will print the best validation accuracy achieved during training.

## Files and Structure

- `train.py`: The main training script.
- `model.py`: Defines the ResNet18 architecture with Preactivation Basic Blocks.
- `utils.py`: Contains the helper function for weight comparison and the training-validation loop.
- `requirements.txt`: Lists the required Python packages.

## Acknowledgments

This project is inspired by the ResNet architecture and the CIFAR-10 dataset. The code structure and comments are designed for educational purposes and ease of understanding.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to fork this repository and customize the code for your own projects.

For any questions or issues, please [open an issue](https://github.com/your-username/resnet-preact-cifar10/issues).

