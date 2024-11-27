# Cats vs Dogs Image Classification

## Project Overview
The goal of this project was to build a deep learning model capable of accurately classifying images as either cat or dog. To do this, I utilized the well-known Cats vs Dogs dataset from kaggle, which provides thousands of labeled images for training and testing. The focus was on implementing a CNN using TensorFlow and Keras, two powerful libraries in Python designed for deep learning applications.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: TensorFlow, Keras, NumPy, Matplotlib, Pandas
- **Dataset**: Cats vs Dogs dataset from Kaggle

## Key Features
- **Data Preprocessing**: Images are resized and normalized before feeding into the CNN model.
- **Model Architecture**: A custom CNN architecture was built, designed specifically for image classification tasks.
- **Model Training**: The model is trained with the Cats vs Dogs dataset using multiple epochs, batch normalization, and other optimizations.
- **Evaluation**: Model performance is evaluated using accuracy, precision, recall, and F1-score metrics.

## Results
- **Accuracy**: Achieved an accuracy of 83.91% on the test set.
- **Loss**: 0.7179.

## How to Run the Project
1. Clone this repository: https://github.com/prathambisht2/Cat-VS-Dog-Classifier.git
2. Install the required libraries: pip install -r requirements.txt
3. Run the Jupyter notebook: jupyter notebook cats_vs_dogs_Image_Classification.ipynb

## Conclusion
This project demonstrates how a deep learning model, specifically a CNN, can effectively classify images of cats and dogs. With fine-tuning, the model achieved impressive accuracy, showcasing the power of neural networks in image classification.
