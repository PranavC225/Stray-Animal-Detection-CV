# Stray-Animal-Detection-CV

A **published (ACIA-2022)** computer-vision system that classifies stray animals to improve safety for visually-impaired users — deployed on a chest-mounted device with audio feedback.

![Published](https://img.shields.io/badge/Published-ACIA--2022-success)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-classical-5C3EE8?logo=opencv&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

> Co-authored group project. Published at **ACIA-2022 (AIP Conference Proceedings)**.
> 📄 Paper: https://doi.org/10.1063/5.0133591

## Why

Visually-impaired pedestrians can't see approaching stray animals, a real safety risk in many environments. This system detects and classifies them from a wearable camera and warns the user through audio feedback.

## What it does

- Classifies stray animals from camera input on a chest-mounted wearable device.
- Preprocessing pipeline: **PCA / SIFT / K-Means**.
- Compares four classifiers — **SVM, KNN, Decision Tree, Random Forest**.
- Provides real-time audio feedback to the user.

## Method & results

Best test accuracy **81.61%** with Random Forest.

| Model | Test accuracy |
|---|---|
| Random Forest | **81.61%** |
| SVM | 81.26%  |
| KNN | 78.27% |
| Decision Tree |76.94% |

## Stack

- **OpenCV** — image handling and feature extraction (SIFT).
- **scikit-learn** — PCA, K-Means, and the four classifiers.
- Classical CV/ML pipeline (pre-deep-learning), tuned to run on a wearable device.

## Links

- 📄 ACIA-2022 paper — https://ui.adsabs.harvard.edu/abs/2023AIPC.2705d0001B/abstract
<!--- Suggested repo topics: `computer-vision` · `machine-learning` · `research`-->
