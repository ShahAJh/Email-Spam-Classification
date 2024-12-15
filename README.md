# Spam Detection Using Multinomial Naive Bayes

## Overview
This project implements a spam detection system for emails based on their provenance (SMTP sender) and content. The dataset used for training and testing is sourced from [Kaggle](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv). The system classifies emails as spam or non-spam using a **Multinomial Naive Bayes (MNB)** model. The results are evaluated using standard classification metrics, with a focus on the **F1-score**.

## Features
- **Dataset Handling**: Automatically cleans and processes the dataset.
- **Spam Detection Model**: Utilizes the Multinomial Naive Bayes classifier.
- **Evaluation Metrics**: Generates a confusion matrix and a detailed classification report.

## Dataset
The dataset includes:
- Email content represented as numeric features.
- A binary label indicating whether the email is spam (1) or non-spam (0).

Link to dataset: [Email Spam Classification Dataset](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)

## Dependencies
To run this project, the following Python libraries are required:
- `pandas`
- `scikit-learn`
- `numpy`



## Analysis
- **Class 0 (non-spam)**: High precision (98%) and recall (95%) indicate the model performs excellently in identifying legitimate emails.
- **Class 1 (spam)**: Strong recall (95%) shows the model effectively detects spam emails, with slightly lower precision (88%) due to false positives.

## Files in Repository
- `email_spam.py`: The main script for implementing and evaluating the model.
- `emails.csv`: The dataset file (download separately if not included).
- `README.md`: Project documentation.

## Future Improvements
- Explore additional preprocessing techniques like stemming or TF-IDF vectorization.
- Compare results with alternative models like Feedforward Neural Networks (FFNN) or MLP.
- Enhance visualization by plotting the confusion matrix.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Dataset provided by [Kaggle](https://www.kaggle.com/).
- Developed as part of a coursework assignment on spam detection.

---
Feel free to reach out with questions or suggestions via GitHub Issues.

