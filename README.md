# Handwritten Character Recognition

This project uses a Convolutional Neural Network (CNN) to recognize handwritten English alphabet characters (A-Z). The model is built and trained using TensorFlow and Keras.

## Project Overview

The project consists of two main parts:
1.  **Model Training**: A Python script (`handwritten_character_recognisation_model.py`) and a Jupyter Notebook (`Handwritten_Character_Recognisation.ipynb`) are used to load the `A_Z Handwritten Data.csv` dataset, preprocess the images, and train a CNN model. The trained model is then saved as `handwritten_character_recog_model.h5`.
2.  **Character Prediction**: The `character_recogniser.py` script loads the pre-trained model to predict the character from a given image file. It processes the input image to the required format and displays the prediction on the image.

## Files

-   `Handwritten_Character_Recognisation.ipynb`: Jupyter Notebook containing the step-by-step process of model creation and training.
-   `handwritten_character_recognisation_model.py`: The script version for training and saving the model.
-   `character_recogniser.py`: Script to load the trained model and predict a character from an image.
-   `handwritten_character_recog_model.h5`: The saved, pre-trained model file.
-   `A_Z Handwritten Data.csv`: The dataset used for training the model.
-   `*.png`: Example image files for prediction.

## Technologies Used

-   Python
-   TensorFlow / Keras
-   OpenCV
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn

## How to Run

### Prerequisites

Make sure you have Python and the required libraries installed.
pip install tensorflow opencv-python pandas numpy matplotlib scikit-learn


### 1. Train the Model (Optional)

If you want to retrain the model, run the training script. This will generate a new `handwritten_character_recog_model.h5` file.

````bash
python handwritten_character_recognisation_model.py

### 2. Run the Recognizer

To predict a character from an image (e.g., G.png), run the recognizer script. Make sure the image file is in the same directory.

A window will pop up showing the image with the predicted character. Press the 'ESC' key to close it.
