# Arabic-Alphabets-Recognition

## Description:
This project focuses on developing a robust Arabic character recognition system using various machine learning algorithms. The dataset consists of flattened pixel values extracted from handwritten Arabic characters, along with corresponding labels indicating the characters.

## Data Exploration and Preparation:

Identified the number of unique classes and examined class distribution.

Normalized each image to ensure consistency in model training.

Implemented a function to reconstruct images from flattened vectors for visualization.


## Experiments and Results:

SVM Model:

Trained an SVM model on the training data.

Evaluated model performance using confusion matrix and average F-1 scores on the testing dataset.

<br>

KNN Model:

Split the training data into training and validation sets.

Explored different K values for KNN models.

Plotted average F-1 scores against K values and selected the optimal K.

Tested the model with the best K value and provided evaluation metrics.

<br>

Neural Network Models:

Developed two distinct neural network architectures.

Trained each model and visualized training/validation error and accuracy curves.

Saved the best-performing model and utilized it for predictions on new, unlabeled data.

Evaluated the best model using confusion matrix and average F-1 scores on the testing dataset.

<br>

Comparison and Conclusion:

Compared the performance of SVM, KNN, and Neural Network models.

Identified the best-performing model based on evaluation metrics, suggesting the most suitable approach for Arabic character recognition.

<br>

## Dataset:
You can download the dataset from [here](https://drive.google.com/file/d/1u3tnEY-eMmeUNaKP31YBCVoty9s5VCsz/view)

<br>

## Team Member:
[Malak Gamal](https://github.com/malakg1)
