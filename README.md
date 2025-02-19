# Mars Terrain Segmentation

## Overview

This project tackles a **semantic segmentation problem** involving **64x128 grayscale images of Mars terrain**. Each pixel is classified into one of five terrain types:

- **0**: Background
- **1**: Soil
- **2**: Bedrock
- **3**: Sand
- **4**: Big Rock

We started with a **U-Net-based model** and progressively improved performance using **data augmentation, custom loss functions, and advanced feature extraction techniques**. Our final model achieved **0.687 accuracy** on the Kaggle leaderboard.

### Key Improvements:
- **Data cleaning**: Removal of outliers (e.g., alien objects in images).
- **Addressing class imbalance**: Weighted loss function emphasizing underrepresented classes.
- **Feature enhancement**: Advanced bottleneck with **dilated convolutions and Squeeze-and-Excitation blocks**.
- **Regularization techniques**: Dropout and L2 regularization to improve generalization.

## Team

**LOS PINGUINOS**: Zeno Peracchione, Daniele Vozza, Francesco Tomasi, Lorenzo Galatea.
