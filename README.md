# Assignment1
# Sampling Assignment - Credit Card Fraud Detection
**Roll Number:** 102316049

## Project Description
This repository contains my submission for the sampling assignment. The goal was to analyze how different sampling techniques affect model accuracy on an imbalanced dataset (Credit Card Fraud Detection).

To ensure unique results, I used my roll number (**102316049**) as the random seed for all operations, including data splitting, balancing, and model initialization.

## Methodology

### 1. Data Preprocessing
The dataset was originally imbalanced. I handled this by oversampling the minority class (Fraud) so that both classes have equal representation before applying any sampling techniques.

### 2. Sampling Techniques
I implemented five different sampling techniques to create training sets:
* **Simple Random Sampling:** Randomly picking data points.
* **Stratified Sampling:** Keeping the class ratio consistent.
* **Systematic Sampling:** Picking every $k^{th}$ record (simulated).
* **Cluster Sampling:** Grouping data and selecting random clusters.
* **Bootstrap Sampling:** Resampling with replacement.

### 3. Models Used
I evaluated the samples using the following models:
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

## Results
The script generates a comparison table and a bar graph showing the accuracy of each model against each sampling technique. Since the random state is fixed to `102316049`, the results are reproducible.

## How to Run
1.  Download the dataset `Creditcard_data.csv` and place it in the same folder as the code.
2.  Run the notebook/script.
3.  The final output will display the accuracy table and the comparison plot.
