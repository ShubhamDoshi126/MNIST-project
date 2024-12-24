# MNIST Project Readme

## Overview
This project demonstrates how to preprocess, visualize, and predict handwritten digits using the MNIST dataset. It includes functionalities for downloading and preparing the dataset, visualizing samples, and testing custom handwritten images.

## Files
1. **module5-2.ipynb**: Jupyter Notebook for downloading, loading, and preprocessing the MNIST dataset.
2. **module5-2.py**: Python script for visualizing MNIST dataset samples.
3. **module5-3.ipynb**: Jupyter Notebook for testing handwritten images against the MNIST model.
4. **module5-3.py**: Python script for preprocessing and predicting custom handwritten images.

## Key Learnings

### Data Loading and Preprocessing
- **Downloading and Loading**: Learn how to download the MNIST dataset and load it into memory.
- **Preprocessing**: Understand how to preprocess images, including normalization and reshaping.

### Visualization
- **Visualizing Samples**: Use Matplotlib to visualize MNIST digit images.
- **Comparing Images**: Display both original and processed images to understand the preprocessing steps.

### Image Processing
- **OpenCV**: Use OpenCV to read, threshold, and resize images.
- **Bounding Box and Padding**: Find the bounding box of digits, add padding, and center the digit in a square image.

### Command-Line Interface
- **Argparse**: Create a CLI to specify dataset type and sample index for visualization.
- **Sys Module**: Use the `sys` module to handle command-line arguments for image file and true digit.

### Integration with MNIST Model
- **Mnist Class**: Integrate preprocessing steps with the `Mnist` class to make predictions on new data.
- **Prediction and Validation**: Test the model's predictions against the true digit and print the results.

## Usage

### Visualizing MNIST Samples
Run the following command to visualize a sample from the MNIST dataset:
python module5-2.py train 42  # Display the 42nd training sample



### Testing Custom Handwritten Images
Run the following command to preprocess and predict a custom handwritten image:
python module5-3.py <image_filename> <true_digit>

Example:
python module5-3.py digit_5.png 5


## Conclusion
This project provides a comprehensive understanding of handling the MNIST dataset, from downloading and preprocessing to visualization and prediction. It demonstrates the integration of various tools and libraries to create a complete workflow for digit recognition.
