# EEG-Based Arm Movement Predictions.

## Overview

This repository contains code for predicting arm movements using EEG data collected from a Muse 2 headset. The research explores global trends and gaps in assistive technology (AT) utilization, leveraging World Health Organization (WHO) data to identify areas for improvement.

## Dataset

The dataset for predicting right arm movements was sourced from Kaggle. It includes EEG signals recorded during arm movement tasks, labeled with corresponding movements.

### Sample Dataset

A sample dataset (`ArmMovementDetection_Dataset.csv`) is included in this repository for testing purposes. It contains pre-processed EEG signals and corresponding arm movement labels.

## Models Explored

The project investigates various machine learning models for predicting arm movements based on EEG data:

1. **Support Vector Machines (SVM)**
   - **Purpose**: Classifies EEG signals into different arm movement categories.
   - **Performance**: Achieved an accuracy rate of X%.

2. **Random Forest**
   - **Purpose**: Uses ensemble learning to predict arm movements.
   - **Performance**: Achieved the highest accuracy of 67.21% among the tested models.

3. **Gradient Boosting**
   - **Purpose**: Boosts weak learners sequentially to enhance predictive accuracy.
   - **Performance**: Achieved an accuracy rate of X%.

4. **Logistic Regression**
   - **Purpose**: Models the probability of each arm movement class based on EEG features.
   - **Performance**: Achieved an accuracy rate of X%.

5. **K-Nearest Neighbors (KNN)**
   - **Purpose**: Classifies arm movements based on similarity to neighboring EEG signal patterns.
   - **Performance**: Achieved an accuracy rate of X%.

## Results

Among the models tested, Random Forest achieved the highest accuracy rate of 67.21% in predicting arm movements from EEG signals. Detailed performance metrics for each model are provided in the respective sections above.

## Contact Information

For questions or collaboration, please contact:
- Email: [malikhamna107@gmail.com](mailto:malikhamna107@gmail.com)
- LinkedIn: [Hamna Malik](https://www.linkedin.com/in/hamnamalik107/)
