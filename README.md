# Image Deblurring Using Autoencoders

## Overview
This project tackles the challenge of image deblurring, aimed at recovering sharp images from their blurred counterparts using autoencoders, a class of neural networks renowned for feature learning. The initiative addresses crucial issues in computer vision, enhancing both image quality and usability.

### Contributors
- Pratyay Dutta
- Aditya Gambhir

## Installation

To set up this project locally, ensure you have Python 3.11 installed along with the following libraries:
- PyTorch
- NumPy
- Skimage
- Matplotlib

You can install the dependencies via pip:

```bash
pip install torch torchvision numpy matplotlib scikit-image
```

## Usage

To start with the training process, run:

```bash
python Autoencoder_training.ipynb
```

For inference on new images:

```bash
python Autoencoder_inference.ipynb
```

Make sure to adjust the paths to datasets and models as per your setup.

## Datasets

This model was trained on:
- CelebA
- HIDE
- WIDEFACE

These datasets were chosen for their diversity, aiding in incremental learning and enhancing the model's generalizability.

## Evaluation Metrics

The model's effectiveness was gauged using:
- Mean Squared Error (MSE)
- Peak Signal to Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)

These metrics facilitated a comprehensive evaluation, showcasing significant improvements in image clarity.

## Results

Upon evaluation, our model showed promising outcomes, with improvements in PSNR and SSIM values indicating enhanced image quality. For detailed results, refer to the `Final report.pdf` and `Final Project.pptx` within this repository.

## Applications

This technique holds potential for broad applications, including but not limited to:
- Photography Enhancement
- Medical Imaging
- Astronomical Imaging

## Contributions

We welcome contributions to improve the model and extend its applicability. Please feel free to fork this repository and submit pull requests.

## Acknowledgments

Special thanks to:
- Djemel Ziou and Alain Hore for insights on image quality metrics.
- Quan Huynh-Thu and Mohammed Ghanbari for their work on PSNR accuracy.
- Olaf Ronneberger, Philipp Fischer, and Thomas Brox for their U-Net architecture insights.

For detailed references, please refer to the `Final report.pdf`.

---
