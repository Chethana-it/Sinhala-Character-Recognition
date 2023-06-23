# Sinhala ML Character Recognition with KNN Algorithm and Tkinter GUI

This project aims to recognize limited Sinhala characters using machine learning techniques, specifically the K-Nearest Neighbors (KNN) algorithm. The application provides a Tkinter graphical user interface (GUI) for easy interaction.

## Features

- Recognition of limited Sinhala characters
- KNN algorithm for classification
- Tkinter GUI for user-friendly experience

## Prerequisites

- Python 3.6 installed
- Required libraries:
  - NumPy
  - OpenCV
  - scikit-learn
  - Tkinter

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Chethana-it/Sinhala-Character-Recognition.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Sinhala-Character-Recognition
   ```

3. Install the required libraries:

   ```bash
   pip install numpy opencv-python scikit-learn
   ```
run the project using jupyter notebook

2. The Tkinter GUI window will appear.

3. Draw the Sinhala character in the provided drawing area using the mouse.

4. Click the "Recognize" button to classify the drawn character.

5. The predicted character label will be displayed on the GUI.

## Dataset

The dataset used for training and testing the model consists of a limited set of Sinhala characters. The dataset is not included in this repository. However, you can create your own dataset or acquire one from publicly available sources.

## Model Training

The model is trained using the KNN algorithm implemented in scikit-learn. The training process involves feature extraction from the input images and training the KNN classifier on the extracted features. Refer to the `train.py` script for more details.


## Acknowledgements

- The authors would like to thank the developers and contributors of scikit-learn, NumPy, OpenCV, and Tkinter for their valuable libraries and tools.

Feel free to modify and enhance this README file according to your project's specific requirements and details.
