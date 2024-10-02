# Fake News Detection

This project is a machine learning model developed by Poicitaco to detect fake news. The model is built using various machine learning algorithms to classify news articles as either "fake" or "real" based on their content.

## Dataset

The dataset used for training the models consists of two files:
- `Fake.csv`: Contains news articles labeled as "fake".
- `True.csv`: Contains news articles labeled as "true".

## Features

Key features of this project include:
- **Text Preprocessing**: Data cleaning, tokenization, and vectorization using TfidfVectorizer.
- **Model Training**: The project utilizes several machine learning algorithms, including:
  - Logistic Regression
  - Decision Tree
  - Gradient Boosting Classifier
  - Random Forest Classifier
- **Model Evaluation**: Models are evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Requirements

To run the notebook, you need the following dependencies:

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

You can install these dependencies by running the following command:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Conclusion
This project demonstrates the effectiveness of different machine learning algorithms in detecting fake news. The results show the potential of machine learning in improving the accuracy of fake news detection systems.

## Authors
Poicitaco

