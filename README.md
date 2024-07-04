# Fruit Image Classifier Using Perceptron

## Description
This project implements a simple perceptron-based classifier to distinguish between images of apples and pears. The classifier is trained using color and roundness features extracted from the images. The perceptron adjusts its weights through an iterative training process until the classification error is minimized.

## Files
- `is_lab_1_template.m`: The main MATLAB script that extracts features from fruit images, trains the perceptron, and classifies the images.
- `is_lab_1.py`: The main Python script that demonstrates a perceptron classifier using randomly generated initial weights and a simple dataset.
- `apple_04.jpg`, `apple_05.jpg`, ..., `apple_19.jpg`: Images of apples used for training and testing.
- `pear_01.jpg`, `pear_02.jpg`, ..., `pear_09.jpg`: Images of pears used for training and testing.

## Usage

### MATLAB Script
1. Place all the apple and pear images in the same directory as `is_lab_1_template.m`.
2. Run the script in MATLAB:
    ```matlab
    is_lab_1_template
    ```
3. The script will output the classification results and display the total error during the training process.

### Python Script
1. Ensure you have Python installed on your system.
2. Run the script in a Python environment:
    ```python
    python is_lab_1.py
    ```
3. The script will output the classification results, display the total error during the training process, and test the trained perceptron on a test dataset.

## Code Explanation

### MATLAB Script
- The script reads images of apples and pears.
- It calculates color and roundness features for each image.
- It selects a subset of these features for training the perceptron.
- A single-layer perceptron is trained using these features and adjusts its weights based on the classification error.
- The total error is calculated and used to update the weights iteratively until the error is minimized.

### Python Script
- The script uses a predefined dataset with features and labels.
- It initializes random weights for the perceptron.
- The perceptron is trained by adjusting the weights based on the classification error.
- The total error is calculated and used to update the weights iteratively until the error is minimized.
- The trained perceptron is then tested on a test dataset, and the total error is displayed.

