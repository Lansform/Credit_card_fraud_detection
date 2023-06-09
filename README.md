# Credit Card Fraud Detection

This project focuses on building a credit card fraud detection system using machine learning algorithms. The goal is to identify fraudulent credit card transactions from a dataset containing both normal and fraudulent transactions.

## Dataset

The dataset used for this project contains credit card transactions, including features such as transaction amount, time, and various anonymized numerical features. The dataset is labeled, with a binary class indicating whether the transaction is normal (0) or fraudulent (1).

The dataset used in this project can be found in kaggle.

## Dependencies

The following dependencies are required to run the code:

Python (version 3.9.7)
Pandas (version 1.3.3)
NumPy (version 1.21.2)
Scikit-learn (version 0.24.2)
Keras (version 2.6.0)
TensorFlow (version 2.6.0)
Matplotlib (version 3.4.3)
Seaborn (version 0.11.2)

You can install the required dependencies using pip:

```
pip install pandas numpy scikit-learn keras tensorflow matplotlib seaborn
```

## Usage

1. Clone the repository:

```
git clone https://github.com/ayushmanZ/credit-card-fraud-detection.git
```

2. Navigate to the project directory:

```
cd credit-card-fraud-detection
```

3. Run the main script:

```
python main.py
```

This will execute the code for training and evaluating the credit card fraud detection models.

## Results

After running the code, the models will be trained and evaluated on the provided dataset. The performance metrics, such as accuracy, F1 score, and confusion matrix, will be displayed in the console or saved to a file.

The results obtained from the models can be used to assess the effectiveness of the credit card fraud detection system and further improve its performance.

F1 score of the XG boost model was highest
