# Personality-Prediction

This repository presents a machine learning model to predict personality traits based on demographic data, specifically age and gender. The model incorporates the Big Five personality traits (Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism).

## Description
- Developed a model that can predict personality traits based on readily available demographic data.
- Explored the relationships between demographic factors and personality traits.
- Utilized advanced machine learning techniques for improved prediction accuracy.

## Model Architecture
The model utilizes two primary algorithms:

- **Logistic Regression**: A classic algorithm for classification tasks, used to predict the probability of an individual belonging to a specific personality trait category based on their age and gender.
- **Support Vector Machine (SVM)**: A powerful algorithm for classification, able to find non-linear relationships between data points and build a hyperplane that effectively separates different personality trait categories.
- **Linear Regression**: A simple yet effective algorithm for regression tasks, used to predict the numerical values of personality traits based on age and gender. It establishes a linear relationship between the independent variables (age and gender) and the dependent variable (personality trait score).
- **K-Nearest Neighbors (KNN)**: A non-parametric algorithm that classifies data points based on their similarity to neighboring points. It's used for both classification and regression tasks. In this project, KNN is explored to predict personality traits by finding individuals with similar demographic features and personality scores.

Models are implemented in Python and optimized using Jupyter Notebook.

## Data and Processing
The project utilizes a publicly available dataset of personality traits and demographic information. The data is pre-processed before model training, including:

- Data cleaning and handling missing values.
- Feature scaling to ensure numerical stability.
- Splitting the data into training, validation, and test sets.

The model's performance is evaluated using various metrics, such as accuracy, precision, recall, and F1 score. The results demonstrate the effectiveness of the model in predicting personality traits based on demographic data.

## Getting Started
To run this project, you will need:

- Python 
- Jupyter Notebook
- Dependencies packages
- Downloaded and processed dataset

**Once you have the required setup, follow these steps:**

- Clone this repository.
- Install the required dependencies.
- Open the Jupyter Notebook file.
- Run the notebook cells in order.
