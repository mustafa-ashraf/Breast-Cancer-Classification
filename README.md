# Breast Cancer Classification 

![Breast Cancer Image](https://surgery.wustl.edu/wp-content/uploads/2022/04/Breast-Cancer-Screening_News-1024x677.png)


This project is focused on building a machine learning model for the classification of breast cancer tumors as benign or malignant. The dataset used in this project contains various features extracted from breast cancer biopsies, and our goal is to develop a predictive model to help in the diagnosis of breast cancer.

## Dataset

The dataset used in this project is sourced from kaggle and consists of the following columns:

- `id`: Unique identifier for each biopsy
- `diagnosis`: The diagnosis of the tumor (M = malignant, B = benign)
- `radius_mean`: Mean of distances from the center to points on the perimeter
- `texture_mean`: Standard deviation of gray-scale values
- ... (other features)

## Data Exploration

Before building the model, we conducted an exploratory data analysis (EDA) to better understand the dataset. Here are some key findings:

- **Dataset Size**: The dataset contains a total of 569 biopsy samples.
- **Data Completeness**: There are no missing values in the dataset, ensuring a clean and reliable dataset for analysis.
- **Feature Insights**: Descriptive statistics of the features revealed important insights about the characteristics of the tumors and their variations.

## Model Building

The model was trained on a portion of the dataset and then rigorously evaluated for its performance. We used various metrics to assess its efficacy, including:

- **Accuracy**: The ratio of correctly predicted instances to the total instances.
- **Precision**: The proportion of true positive predictions among all positive predictions.
- **Recall**: The proportion of true positive predictions among all actual positives.
- **F1-Score**: The harmonic mean of precision and recall, providing a balanced measure of a model's performance.

## Results

After extensive training and evaluation, our final breast cancer classification model achieved an accuracy of 94%. This accuracy showcases the model's strong predictive power in distinguishing between benign and malignant breast tumors. The precision, recall, and F1-score also validate its effectiveness in providing reliable classifications.

## Conclusion

In conclusion, our breast cancer classification model, developed through rigorous data exploration and machine learning techniques, has shown promising results. It offers a valuable tool for the accurate classification of breast tumors as either benign or malignant. We hope that this project can contribute to the field of medical diagnostics and help healthcare professionals in making more informed decisions.
