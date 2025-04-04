# A Deep Neural Network Model for Image Classification

Welcome to the Deep Neural Network Model for Image Classification project! This repository contains the implementation of a customizable L-layer deep neural network designed to classify whether an image is a cat or not.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project leverages a customizable L-layer deep neural network to perform binary classification on images built from first principle. The primary objective is to determine if an image contains a cat. Deep neural networks, with their ability to learn complex patterns, are particularly effective for this image classification task.

## Dataset

The dataset used for training and testing the model consists of images labeled as either "cat" or "not cat." The images are preprocessed to a fixed size and standadized to enhance the model's performance.

## Model

The deep neural network model is implemented using the following steps:
1. **Data Preprocessing:** Resize images, standardize pixel values, and optionally convert to grayscale.
2. **Feature Extraction:** Flatten images into 1D arrays or use convolutional layers for feature extraction.
3. **Model Architecture:** Configure a customizable L-layer deep neural network with options for various activation functions.
4. **Training:** Use backpropagation and optimization algorithms to minimize the loss function.
5. **Evaluation:** Assess model performance using metric such as accuracy.

## Installation

To run the project locally, please follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SegunDada/deep-neural-network-image-classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd deep-neural-network-image-classification
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To classify an image using the trained deep neural network model:

1. Ensure the image is in the `image/` directory.
2. Create your own dataset or use the default and customize how many perceptron layer you intend. Test the model by adding your image on line 19
3. The output will display whether the image is classified as "cat" or "not cat."

## Results

The model achieved an accuracy of 80% on the test dataset. Detailed results and performance metrics can be found in the main jupyter note file.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize and expand upon this draft to better fit your project. If you need any further assistance, don't hesitate to ask!
