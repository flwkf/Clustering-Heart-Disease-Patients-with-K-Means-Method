# Clustering Heart Disease Patients with K-Means Method

This repository contains a project that was developed to meet the requirements of a mid-semester exam. The project's main objective is to cluster heart disease patients based on 11 contributing factors. 

## Data Columns
The dataset includes the following columns:

1. `id`: Identifier
2. `age`: Age of the patient
3. `sex`: Gender of the patient (0 for female, 1 for male)
4. `cp`: Chest pain type (0-3)
5. `trestbps`: Resting blood pressure (in mm Hg)
6. `chol`: Serum cholesterol level (in mg/dl)
7. `fbs`: Fasting blood sugar > 120 mg/dl (1 for true, 0 for false)
8. `restecg`: Resting electrocardiographic results (0-2)
9. `thalach`: Maximum heart rate achieved
10. `exang`: Exercise-induced angina (1 for yes, 0 for no)
11. `oldpeak`: ST depression induced by exercise relative to rest
12. `slope`: Slope of the peak exercise ST segment

## Data Preprocessing
For the data preprocessing, we used all columns except the `id` column for modeling. Principal Component Analysis (PCA) was applied to reduce the dimensionality of the data to 2 dimensions, making it more suitable for K-Means clustering.

## Clustering with K-Means
K-Means clustering was applied to group heart disease patients into distinct clusters based on their characteristics and risk factors. The K-Means algorithm divides the dataset into clusters to identify patterns and similarities among patients.

## Usage
You can clone this repository and explore the code to understand the process and results of clustering heart disease patients using the K-Means method.

Feel free to reach out if you have any questions or need further information.

