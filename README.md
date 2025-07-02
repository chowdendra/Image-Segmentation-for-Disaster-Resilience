# Disaster Image Segmentation for Resilience

This project uses deep learning-based image segmentation to detect and classify disaster-affected regions from satellite and drone imagery. The goal is to support faster emergency response and accurate damage assessment after natural disasters such as floods, earthquakes, and wildfires.

## Project Overview

- Objective: Segment and classify affected areas in post-disaster images using U-Net and pretrained models.
- Outcome: A fine-tuned segmentation model capable of highlighting damaged regions with high accuracy using metrics like IoU and Dice Coefficient.

## Highlights

- Processed and visualized satellite disaster datasets (xBD, FloodNet)
- Trained baseline U-Net model with data augmentation
- Fine-tuned U-Net with pretrained encoders (ResNet, VGG)
- Addressed class imbalance using focal loss
- Evaluated on unseen test data with visual comparisons
- Final model achieves high segmentation accuracy

## Tools and Technologies

- Languages/Frameworks: Python, TensorFlow/Keras
- Libraries: NumPy, Pandas, OpenCV, Matplotlib, Seaborn
- Models: CNN, U-Net, ResNet/VGG + U-Net
- Environment: Google Colab, Jupyter Notebook
- Version Control: Git, GitHub

## Evaluation Metrics

- Intersection over Union (IoU)
- Dice Coefficient
- Visual Output Comparison

## Results

- Side-by-side comparison of input images, ground truth masks, and predicted masks
- Improved accuracy and segmentation detail after transfer learning and hyperparameter tuning



