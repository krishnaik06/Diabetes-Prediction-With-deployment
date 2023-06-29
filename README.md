# Diabetes Prediction with Deployment

This repository contains a machine learning project for predicting diabetes using a Random Forest classifier. The project includes training a model on the "diabetes.csv" dataset and deploying the model for making predictions.

## Dataset

The dataset used for this project is the "diabetes.csv" file located in the "Dataset" folder. It contains various features related to diabetes, such as glucose level, blood pressure, insulin level, and body mass index (BMI), along with the outcome indicating whether a patient has diabetes or not.

## Installation

To run the code in this repository, you need to have the following dependencies installed:

- Python (version 3.7 or higher)
- pandas
- scikit-learn
- joblib

You can install the required packages by running the following command:


## Usage

1. Clone the repository to your local machine:


2. Navigate to the repository's directory:


3. Run the "train_model.py" script to train the Random Forest model and save it:


4. The trained model will be saved as "trained_model.pkl" in the repository.

5. Use the trained model for making predictions by running the "predict.py" script:


## Results

After training the model and making predictions, the following results can be observed:

- Accuracy: 72%
- Confusion Matrix:

![image](https://github.com/niravpatidar37/Diabetes-Prediction-With-deployment/assets/51831628/5d415707-ee76-4838-a544-e80ae210dbff)

- Feature Importance:

- ![image](https://github.com/niravpatidar37/Diabetes-Prediction-With-deployment/assets/51831628/f5583e25-4452-4efb-b56a-e2f9c1b6fda5)

- ROC Curve
- ![image](https://github.com/niravpatidar37/Diabetes-Prediction-With-deployment/assets/51831628/5b451eec-50fb-4b1d-a24c-22f492b50fa8)

## Contributing

Contributions to this project are welcome. If you find any issues or have ideas for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

