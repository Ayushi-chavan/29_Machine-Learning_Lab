# Machine Learning Lab 6

## Practical 6 – Implementation of Neural Network Classification

### Aim
To implement a neural network model for classification using the Seeds dataset.

### Objective
To understand neural network architecture, activation functions, model training, and classification performance evaluation.

### Dataset
The practical uses the `seeds.csv` dataset, which contains seed features used to classify samples into three classes.

### Files Included
- `ML_Lab6.ipynb` – Jupyter Notebook containing the implementation.
- `seeds.csv` – Dataset used for training and testing.
- `README.md` – Description of the practical.

### Tools and Libraries
- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

### Practical Work
- Loaded and explored the Seeds dataset.
- Prepared and scaled the input features.
- Created a sequential neural network with two hidden layers.
- Used ReLU activation in the hidden layers and Softmax in the output layer.
- Trained the model using training data and early stopping.
- Compared actual and predicted class labels.
- Evaluated model performance using accuracy and precision.

### Model Architecture
- Input layer: 7 features
- Hidden layer 1: 16 neurons with ReLU activation
- Hidden layer 2: 8 neurons with ReLU activation
- Output layer: 3 neurons with Softmax activation

### Conclusion
The practical demonstrates the implementation of a neural network for classifying the Seeds dataset into three classes. The model was trained using scaled features and evaluated by comparing actual and predicted labels using classification metrics.
