# tnsdc_genai
## Breast Cancer Detection using Neural Network

### Introduction
This Python program aims to detect breast cancer using a neural network model. The dataset used is the Breast Cancer Wisconsin (Diagnostic) Data Set, which is available in the scikit-learn library. The program preprocesses the data, trains a neural network model, evaluates its performance, and provides predictions.

### Features
- **Data Loading**: The program loads the breast cancer dataset from scikit-learn.
- **Data Preprocessing**: It converts the dataset into a pandas DataFrame, adds labels, checks for missing values, and performs statistical analysis.
- **Model Training**: The neural network model is trained using TensorFlow and Keras.
- **Model Evaluation**: It evaluates the model's performance using accuracy metrics and loss functions.
- **Prediction**: The trained model is used to predict whether a tumor is malignant or benign based on input data.

### How to Use
1. Ensure you have Python installed on your system.
2. Install the necessary libraries such as numpy, pandas, matplotlib, scikit-learn, and TensorFlow.
3. Copy the provided code into a Python file (e.g., `breast_cancer_detection.py`).
4. Run the file using a Python interpreter.

### Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn
- TensorFlow
- Keras

### Example Usage
```python
# Run the Python script
python breast_cancer_detection.py
```

### Output
The program will display the model's accuracy and loss during training. It will also provide predictions for the given input data, indicating whether the tumor is malignant or benign.

### Contribution
Contributions to enhance the functionality or performance of this breast cancer detection program are welcome. Please feel free to fork this repository and submit pull requests with your improvements.

### License
This program is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
