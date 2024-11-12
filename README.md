# BERT Email Spam Classifier

A deep learning model using BERT for email spam classification, achieving 94% accuracy.

## Description

This project implements an email spam classification system using Google's BERT model. It effectively distinguishes between spam and legitimate emails through transfer learning and fine-tuning on a balanced email dataset.

https://github.com/pushparajanrahul/Spam_Classifier_BERT_24_H768/blob/main/images/Confusion%20Matrix.png

We have used a open dataset [Spam Mails Dataset][reference] from Kaggle for this task

## Dependencies

```
Python 3.8+
TensorFlow 2.13.0
TensorFlow Hub 0.14.0
TensorFlow Text 2.13.0
Pandas
NumPy
Scikit-learn
```

## Installing

```
git clone https://github.com/yourusername/bert-spam-classifier.git

# Navigate to the project directory
cd bert-spam-classifier

# Install required packages
pip install -r requirements.txt
```

## Model Performance

- Overall Accuracy: 94%
- Precision: 96%
- Recall: 93%
- F1-Score: 94%


## Acknowledgments

[BERT Paper](https://arxiv.org/abs/1810.04805)
[TensorFlow Hub](https://www.kaggle.com/models/tensorflow/bert/tensorFlow2/bert-en-uncased-l-10-h-768-a-12)
[reference]:https://www.kaggle.com/datasets/venky73/spam-mails-dataset?resource=download

