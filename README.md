# YoungDevInterns_Machine_Learning_Task_7
 Develop a Neural Network for Classification  Task: Build and train a neural network.  Details:  Use TensorFlow or PyTorch to create a neural network for a classification task.  Train the model and evaluate its performance on a test set

📌 Overview
This project demonstrates a Deep Neural Network (DNN) built using TensorFlow/Keras to classify cereals into Low, Medium, and High rating categories based on nutritional data.

📊 Dataset
Source: preprocessed_cereal.csv

Target: rating_class (created by binning original rating)

Classes: Low, Medium, High

Features: Calories, sugar, fat, etc.

⚙️ Methodology
🔹 Preprocessing
Binned continuous rating values into categories

Encoded class labels using LabelEncoder → One-hot encoded using to_categorical

Normalized features with StandardScaler
🔹 Training Details
Optimizer: Adam

Loss Function: Categorical Crossentropy

Metrics: Accuracy

Epochs: 50

Batch Size: 8

Validation Split: 10%
