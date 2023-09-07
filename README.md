# Car Purchase Prediction using Neural Network

This is a Python code example for predicting car purchases using a neural network. The code uses TensorFlow and scikit-learn for data preprocessing and model evaluation.

## Getting Started

These instructions will help you run the code on your local machine for development and testing purposes.

### Prerequisites

Before running the code, make sure you have the following libraries installed:

- numpy
- pandas
- tensorflow
- scikit-learn
- matplotlib


## Data

The dataset used for this project is stored in the `car_data.csv` file. It contains information about car purchases, including features such as gender, age, and income.

### Data Preprocessing

- Gender is converted to numerical values (0 for Male, 1 for Female).
- Features are scaled using Min-Max scaling.

## Model

A neural network model is created with the following architecture:

- Input Layer (30 units, ReLU activation)
- Hidden Layer 1 (15 units, ReLU activation)
- Hidden Layer 2 (15 units, ReLU activation)
- Output Layer (1 unit, Sigmoid activation)

The model is compiled using binary cross-entropy loss and the Adam optimizer. It is trained on the data for 100 epochs.

## Model Evaluation

- Classification report and confusion matrix are used to evaluate the model's performance on the test data.
- Predictions are made on the test data, and a threshold of 0.5 is used to classify the results.

## Results

The code generates a plot of the training loss over epochs and provides classification metrics for model evaluation.
The model guessed 298 out of 330 correctly

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

