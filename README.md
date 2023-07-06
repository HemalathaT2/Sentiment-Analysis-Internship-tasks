
## Sentiment Analysis of Restaurant Feedback


This repository contains the code and documentation for sentiment analysis of restaurant feedback. The goal of this project is to analyze customer reviews and determine the sentiment associated with each feedback, whether it is positive, negative, or neutral.

## Project Overview

The objective of this project is to perform sentiment analysis on restaurant feedback using the Naive Bayes classifier. By analyzing customer reviews, we aim to gain insights into customer sentiments and understand their satisfaction levels.

## Dataset

The dataset used for this project consists of customer feedback collected from various restaurants was provided to me by Radix Educational Trust. It contains a collection of text reviews along with corresponding sentiment labels. The dataset has been preprocessed to remove any irrelevant information and is divided into a training set and a test set for model evaluation.

## Naive Bayes Classifier

The Naive Bayes classifier is a probabilistic machine learning model commonly used for text classification tasks, including sentiment analysis. It leverages the Bayes' theorem and assumes that features (words) are conditionally independent given the class label.

In this project, we have implemented the Naive Bayes classifier using the scikit-learn library in Python. The classifier has been trained on the preprocessed restaurant feedback dataset to learn the relationship between words and sentiment labels.

## Results

The sentiment analysis task yielded the following results:

- Accuracy: 72%
- Precision: 85.3%
- Recall: 62.74%
- F1-score: 72.3%

The analysis has provided valuable insights into customer sentiment towards restaurants. The Naive Bayes classifier has shown promising performance in accurately classifying sentiment in customer feedback.

## Usage

To use the sentiment analysis model and reproduce the results, follow these steps:

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/HemalathaT2/Sentiment-Analysis-Internship-tasks.git
   ```

2. Install the required dependencies mentioned in the `requirements.txt` file.
   ```bash
   pip install -r requirements.txt
   ```

3. Run the `sentiment_analysis.py` script, providing the necessary input data and parameters.
   ```bash
   python sentiment_analysis.py --input data/reviews.csv --output results/sentiment_results.csv
   ```

4. Examine the generated output file (`results/sentiment_results.csv`) to view the sentiment analysis results.

## Contributing

Contributions to this project are welcome! If you have any suggestions, ideas, or improvements, please open an issue or submit a pull request. Any contribution to enhance the model's performance, explore alternative algorithms, or improve the documentation is highly appreciated.

## License

This project is licensed under the [MIT License](LICENSE).
```

Please note that you may need to customize the file paths, commands, and other details according to your specific project structure and requirements.
