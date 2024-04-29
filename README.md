# Personalized Cancer Diagnosis Using Machine Learning

## Overview
This project aims to automate the classification of genetic mutations involved in cancer development, distinguishing between driver mutations, which contribute to tumor growth, and passenger mutations, which are neutral. This is crucial for genomic scientists who traditionally rely on extensive literature review, a process that is both slow and labor-intensive. Our solution utilizes a machine learning ensemble classifier to streamline this task.

## Data
The dataset employed for this analysis includes the following components:
- **Gene**: The specific gene involved in the mutations.
- **Variation**: The type of amino acid variation.
- **Text**: Clinical evidence that supports the classification of the genetic mutations.

The dataset is available for download [here](https://www.kaggle.com/c/msk-redefining-cancer-treatment/data).

## Methodology
Our approach combines classical machine learning algorithms and advanced deep learning techniques:
- **Classical Algorithms**: K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression.
- **Deep Learning Models**: Recurrent Neural Networks (RNN), Convolutional Neural Networks (CNN), and Long Short-Term Memory (LSTM) networks.

Through extensive experimentation, Random Forest emerged as the most effective model for our specific dataset.

## Performance Metrics
To evaluate the effectiveness of our models, we use the following metrics:
- **Log Loss**: Measures the accuracy of the classifier. The lower the log-loss, the better the model's predictions.
- **Confusion Matrix**: Provides a summary of prediction results on a classification problem. The number of correct and incorrect predictions are summarized with count values and broken down by each class.


<img width="467" alt="image" src="https://github.com/chiranjeevH/Cancer-Diagnosis-Using-ML/assets/65659686/11ccd3ba-2f7e-4377-aa58-a7e59daab51b">

<img width="440" alt="image" src="https://github.com/chiranjeevH/Cancer-Diagnosis-Using-ML/assets/65659686/11a108af-5260-4a52-a3ce-0e49b9d2f377">

<img width="481" alt="image" src="https://github.com/chiranjeevH/Cancer-Diagnosis-Using-ML/assets/65659686/f90f2057-76d7-45a3-9979-4d0e03f53191">

## Conclusion
The use of machine learning to automate mutation classification significantly accelerates the process of identifying actionable genetic alterations in cancer treatment, potentially leading to more personalized and timely therapeutic strategies.

