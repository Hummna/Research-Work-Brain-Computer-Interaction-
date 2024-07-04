# Brain-Computer Interaction for Arm Movement Prediction

## Overview

This repository contains research and code for EEG-based arm movement prediction using machine learning models. The research investigates global trends and gaps in assistive technology (AT) utilization, leveraging data from the World Health Organization (WHO) to identify areas for improvement. It then focuses on developing machine learning models for predicting right arm movements using EEG data collected from a Muse 2 headset.

## Dataset

Data for predicting right arm movements was sourced from a Kaggle dataset collected using an EEG sensor from a Muse 2 headset. The dataset includes EEG signals recorded during arm movement tasks, labeled with corresponding movements.

### Sample Dataset

A sample dataset (`right_arm_movements.csv`) is included in this repository for testing purposes. This dataset contains pre-processed EEG signals and corresponding arm movement labels.

## Models Explored

The project explores various machine learning models to predict arm movements based on EEG data:

1. **Support Vector Machines (SVM)**
   - **Purpose**: Classifies EEG signals into different arm movement categories.
   - **Performance**: Achieved an accuracy rate of X% in predicting arm movements.

2. **Random Forest**
   - **Purpose**: Utilizes ensemble learning to predict arm movements from EEG data.
   - **Performance**: Achieved the highest accuracy rate of 67.21% among the models tested.

3. **Gradient Boosting**
   - **Purpose**: Boosts weak learners sequentially to improve predictive accuracy.
   - **Performance**: Achieved an accuracy rate of X% in predicting arm movements.

4. **Logistic Regression**
   - **Purpose**: Models the probability of each class of arm movement based on EEG features.
   - **Performance**: Achieved an accuracy rate of X% in predicting arm movements.

5. **K-Nearest Neighbors (KNN)**
   - **Purpose**: Classifies arm movements based on similarity to neighboring EEG signal patterns.
   - **Performance**: Achieved an accuracy rate of X% in predicting arm movements.

## Code Structure

The code is organized as follows:

