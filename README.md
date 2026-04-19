# Performance Evolution of CNN and ViT with Scaled-Down CIFAR-10 Training Data

## Intro

The research question of this project is whether the classification accuracy of ViT will be less than CNN as the training data volume of CIFAR-10 is scaled down from 100% to an extreme low level of 10%.

Our primary objective is to evaluate these two model under a controlled and fair constraints, comparing the change of classification accuracy across various data scales.

Also it is necessary to investigate that the reason of ViT's failure in toy dataset is a lack of convergence or an overfitting of the limited training dataset.

## Environment

1. Running in GPU T4 \times 2 using Kaggle.
2. Important Dependency:

* OpenCV (cv2) version: 4.13.0
* PyTorch version: 2.10.0
* Torchvision version: 0.25.0
* NumPy version: 2.0.2
* Matplotlib version: 3.10.0
* Scikit-learn version: 1.6.1

## Experience Results


