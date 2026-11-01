# CAI421 – xBD Building Damage Classification

## Project Description
This project uses deep learning to classify satellite building damage into four classes:
- No damage
- Minor damage
- Major damage
- Destroyed

The project compares a Baseline ResNet-50 model with a Siamese ResNet-50 model and evaluates robustness under image degradation.

## Requirements
The required Python libraries are listed in `requirements.txt`.

## Dataset
The project uses the xBD dataset. The dataset archive must be placed in Google Drive at:

`MyDrive/CAI421_Project/xBD/archives/train_images_labels_targets.tar`

## How to Run
1. Open the Python code in Google Colab.
2. Mount Google Drive when prompted.
3. Make sure the dataset archive is available at the path above.
4. Run the code cells in order.

## Reproducibility
The random seed is set to 42 for reproducibility.
The models are trained for 5 epochs with a batch size of 16.
