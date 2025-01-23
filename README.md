# Animal Image Classifier with Adversarial Attacks

This project uses a ResNet-18 model to classify images from the "Animals-10" dataset and evaluates the performance under adversarial attacks. The code also includes data transformations, visualization of images, and the training loop with integration to Weights & Biases (W&B) for tracking metrics.

## Installation

To get started, install the necessary dependencies:

```bash
pip install datasets torch torchvision matplotlib tqdm scikit-learn wandb torchattacks
