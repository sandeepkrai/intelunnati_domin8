# Fashion MNIST Classification with CNN and Intel Optimizations

This repository contains the code and documentation for the project "Fashion MNIST Classification with CNN and Intel Optimizations." The project aims to develop a Convolutional Neural Network (CNN) model to classify fashion images from the Fashion MNIST dataset. The model's performance is further improved by incorporating Intel optimizations, leveraging the power of Intel processors.

## Project Highlights

- Developed a CNN model architecture for fashion image classification using TensorFlow and Keras.
- Integrated Intel optimization libraries, including Intel Math Kernel Library (MKL) and Intel Distribution for Python, to enhance model performance.
- Preprocessed and normalized the Fashion MNIST dataset for training and testing the model.
- Trained the model using the Adam optimizer and evaluated its performance using accuracy as the primary metric.
- Achieved a final accuracy of 92% on the testing set.
- Collaborated within a multidisciplinary team, sharing knowledge through talks and workshops on Flutter, a framework used in the project.

## Repository Structure

The repository is structured as follows:

- `code/`: Contains the Python code for training the Fashion MNIST model, utilizing CNN and Intel optimizations.
- `data/`: Contains the Fashion MNIST dataset.
- `docs/`: Contains the project documentation, including the project report and any additional resources.
- `models/`: Contains the saved models, including the TensorFlow model and the optimized model using Intel optimizations.
- `README.md`: The README file that provides an overview of the project and repository.

## Prerequisites

To run the code in this repository, the following dependencies are required:

- Python 3.x
- TensorFlow
- Keras
- Intel Math Kernel Library (MKL)
- Intel Distribution for Python

Please ensure that the necessary libraries and dependencies are installed before executing the code.

## Usage

1. Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/sandeepkrai/intelunnati_domin8.git
   ```

2. Set up the required dependencies as mentioned in the Prerequisites section.

3. Navigate to the `domin8_MIT_Conquering Fashion MNIST with CNNs using Computer Vision/` directory and execute the Python script to train the Fashion MNIST model:
   ```
   python ./Baseline and Confusion Matrix.py
   ```

4. After training, the model will be saved in the `models/` directory.

5. Optionally, if you want to optimize the model using Intel optimizations, follow the instructions in the code comments or refer to the project documentation in the `docs/` directory.

