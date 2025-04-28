# Breast Cancer Prediction using Logistic Regression

This project applies **logistic regression** to predict whether a given breast cancer cell is **malignant** or **benign** based on the **Breast Cancer Wisconsin** dataset.

## Table of Contents
- [Project Description](#project-description)
- [Installation](#installation)
- [Model Performance](#model-performance)
- [License](#license)

## Project Description
The Breast Cancer Wisconsin dataset contains several attributes for each cell, such as radius, texture, perimeter, and area. Using logistic regression, this project classifies cells as either malignant or benign based on these attributes. The model achieves an **accuracy of 98%** on test data.

## Installation
To run this project locally, you'll need Python and several dependencies. Follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hassan34234234/Breast-Cancer-Prediction.git

2. **Navigate to the project directory:**
   ```bash
   cd Breast-Cancer-Prediction

4. **Install the dependencies: You can install the necessary Python libraries by running:**
      ```bash
   pip install -r requirements.txt

After running the code, you can predict the class of a given cell by inputting its measurements. The output will tell you whether the cell is malignant (1) or benign (0).

**Model Performance**
The model achieves an accuracy of 98% on the test dataset, demonstrating its ability to predict with high reliability. Below are the detailed evaluation metrics:

Accuracy: 0.98
Precision: 0.98
Recall: 0.97
F1-score: 0.97

License
This project is licensed under the MIT License. See the LICENSE file for more details.
