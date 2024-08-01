# Malaria-Parasite-Prediction-Using-Deep-Learning-Approach

This project explores the use of convolutional neural networks (CNNs) to automatically detect malaria parasites in microscopic blood smear images. The code implements five different CNN architectures with varying depths (1-5 convolutional layers) to investigate the impact of model complexity on classification accuracy.

Key Files
malaria_parasite_detection.ipynb: Google Colab Notebook containing the main code for data loading, preprocessing, model building, training, evaluation, and visualization.

The Malaria dataset contains two folders:
Infected: Images of blood smears containing malaria parasites.
Uninfected: Images of blood smears without malaria parasites.

Code Structure

Data Loading and Preprocessing:
Load the dataset using TensorFlow Datasets.
Preprocess images (resize, normalize).
Split into training and test sets.

Model Building:
Define five custom CNN architectures with increasing complexity (1-5 convolutional layers).
Compile models with appropriate optimizer, loss function, and metrics.

Model Training:
Train each model using the training set.
Employ early stopping to prevent overfitting.

Model Evaluation:
Evaluate each model's performance on the test set.
Calculate accuracy, precision, recall, F1-score.
Generate confusion matrices for visual analysis.


Disclaimer
This project is for educational and research purposes only. It is not intended to be used for clinical diagnosis.
