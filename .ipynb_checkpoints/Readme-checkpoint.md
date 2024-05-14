# Cancer Diagnosis Prediction

This project aims to predict cancer diagnosis (malignant or benign) using machine learning techniques. The dataset used in this project is `cancer.csv`.

## Dataset
The dataset `cancer.csv` contains information regarding various features related to tumors and their diagnosis. The target variable is `diagnosis`, where 1 represents malignant tumors and 0 represents benign tumors.

## Setup
To run this project, ensure you have Python installed along with the following libraries:
- pandas
- scikit-learn
- TensorFlow

You can install these dependencies using pip:
`pip install pandas scikit-learn tensorflow`


## Usage
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the Python script to execute the model.

`python cancer_prediction.py`

## Implementation Details
- The dataset is loaded using pandas.
- Features (x) and target (y) variables are separated.
- The dataset is split into training and testing sets using train_test_split from scikit-learn.
- A Sequential model is created using TensorFlow's Keras API.
- The model architecture consists of Dense layers with sigmoid activation.
- The model is compiled with Adam optimizer and binary crossentropy loss.
- Training is performed for 2000 epochs.

## Contributors
Gonçalo Alves

## License
This project is licensed under the MIT License.