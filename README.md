# Fraud Detection Project

## Description

The Fraud Detection Project is a machine learning-based approach to identifying and preventing fraudulent transactions in financial data. This project leverages various classification models, including Isolation Forest, Autoencoders, Random Forest, SVM, and Neural Networks, to detect anomalies in transaction data and improve the accuracy of fraud detection.

## Project Overview

Financial fraud is a significant challenge faced by financial institutions worldwide. This project aims to develop robust machine learning models to detect potentially fraudulent transactions. The key components of the project include data preprocessing, feature engineering, model training, evaluation, and comparison of various machine learning algorithms.

## Datasets

The project uses two datasets: fraudTrain.csv and fraudTest.csv, which contain transaction data. These datasets are preprocessed to handle missing values, categorical variables, and date-time features for effective model training.

## Features

- **Date and Time**: The timestamp of each transaction.
- **Credit Card Number**: The identifier for each credit card.
- **Merchant and Category**: Information about the transaction merchant and category.
- **Amount**: The transaction amount.
- **Customer Information**: Includes first name, last name, gender, address, job, and date of birth.
- **Geographic Information**: Latitude and longitude of both the transaction and the merchant's location.
- **Other Features**: Unique transaction ID, Unix time of the transaction.

## Project Structure

1. **Data Preprocessing**:
   - Cleaning and transforming the data.
   - Handling missing values and categorical data.
   - Extracting features from the date-time column.

2. **Feature Engineering**:
   - Creating additional features such as transaction time components (year, month, day, hour).
   - Encoding categorical features.

3. **Model Training**:
   - Training various machine learning models such as Isolation Forest, Autoencoders, Random Forest, SVM, and Neural Networks.
   - Using LazyClassifier to evaluate and compare multiple models efficiently.

4. **Model Evaluation**:
   - Evaluating models based on precision, recall, accuracy, and ROC-AUC score.
   - Comparing the performance of different models to identify the best-performing one.

5. **Results and Analysis**:
   - Visualizing model performance.
   - Analyzing feature importance.

## Requirements

- Python 3.7 or above
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- tensorflow
- lazypredict

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Fraud-Detection-Project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Fraud-Detection-Project
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter notebook to preprocess the data and train the models:

    ```bash
    jupyter notebook Fraud_Detection.ipynb
    ```

2. Evaluate the models and visualize the results.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or raise an issue if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to all the contributors and open-source projects that made this project possible.

## Contact

If you have any questions or feedback, feel free to reach out to me at [your email].
