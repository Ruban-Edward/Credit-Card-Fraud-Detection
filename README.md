# Credit-Card-Fraud-Detection
<img src="img/credit-card-fraud-detection.png">

> Credit card companies must accurately detect fraudulent transactions to protect customers from unauthorized charges. This project focuses on developing a machine learning model to identify such fraudulent transactions.

> The dataset used in this project contains credit card transactions made by European cardholders in September 2013. It includes transactions from a span of two days, with a total of 284,807 transactions, out of which 492 are identified as fraudulent. This makes the dataset highly imbalanced, with frauds accounting for only 0.172% of all transactions.

## <h2>Get Started with </h2>

```bash
https://github.com/Ruban-Edward/Credit-Card-Fraud-Detection
```
## <h3>Dataset Description</h3>
The dataset consists of numerical input variables resulting from a Principal Component Analysis (PCA) transformation. Due to confidentiality, the original features and additional background information are not provided. The dataset includes the following features:

* V1, V2, ..., V28: Principal components obtained through PCA.
* Time: The seconds elapsed between each transaction and the first transaction in the dataset.
* Amount: The transaction amount, which can be used for cost-sensitive learning.
* Class: The response variable, taking the value 1 for fraud and 0 otherwise.

## <h3>Project Structure</h3>

* `notebooks` : Jupyter notebooks for data exploration, preprocessing, and model training.
* ``README.md`` : Project documentation.

## <h2>Installation</h2>
To run this project locally, follow these steps:
1. **Clone this Repository** :
   ```bash
   git clone https://github.com/Ruban-Edward/Credit-Card-Fraud-Detection
   ```

2. **Install Python** :
   
   Arch Linux
   ```bash
   sudo pacman -S python
   ```
   Windows
   ```bash
   https://www.python.org/downloads/
   ```
4. **Create a virtual environment** :
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
5. **Install required pip libraries**
   * numpy
   * pandas
   * matplotlib
   * seaborn
   * scikit-learn
   ```bash
   pip install <above packages name>
   ```

6. Open the Jupyter notebook to run the Project
   ```bash
   jupyter notebook
   ```
   
## <h2>Evaluation Metrics</h2>

* Precision: The proportion of true positive predictions among all positive predictions.
* Recall: The proportion of true positive predictions among all actual positives.
* F1-Score: The harmonic mean of precision and recall.
* ROC-AUC: The area under the receiver operating characteristic curve.

## <h2>Acknowledgements</h2>

Download the Dataset from the Kaggle
```
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
```

## <h2>Licence</h2>
[MIT license](LICENSE)


