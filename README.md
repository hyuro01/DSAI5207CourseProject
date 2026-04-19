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

1. CNN
<img width="1238" height="1575" alt="CNN_result" src="https://github.com/user-attachments/assets/ecce1eb9-a8ff-4928-b6d1-fbef7b0337da" />

2. ViT
<img width="1229" height="1575" alt="ViT_result" src="https://github.com/user-attachments/assets/951258f8-efeb-4ddf-8b21-e96e4171c045" />
