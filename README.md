
➡️ [Jump to How to Run](#how-to-run)

A simple yet effective deep learning project demonstrating how to build an image classifier to distinguish between wolves and huskies using the `fastai` library.

## Overview

This Jupyter Notebook provides a complete, end-to-end example of a computer vision task. It automates the process of data collection, model training, and prediction, making it an excellent starting point for anyone interested in practical deep learning.

The key challenge of this project is differentiating between two visually similar animals, which requires the model to learn subtle features.

### Key Features

* **Data Collection:** Automatically downloads images of wolves and huskies from DuckDuckGo.
* **Model Training:** Trains a Convolutional Neural Network (CNN) using a pre-trained ResNet-18 architecture.
* **Transfer Learning:** Leverages the power of transfer learning with `fastai`'s `fine_tune` method to achieve high accuracy quickly.
* **Prediction:** Includes a simple example of how to use the trained model to predict the class of a new image.

## Technologies Used

* fastai
* PyTorch
* DuckDuckGo Search

## How to Run

1.  Ensure you have the required libraries installed. You can install them with:
    ```bash
    pip install fastai "duckduckgo_search>=4"
    ```
2.  Run the cells in the Jupyter Notebook (`wolf-or-husky.ipynb`) sequentially.
3.  Before the last cell (the one where we use the trained model), make sure to copy an image of a husky or a wolf to the same directory as this .ipynb file, and enter its filename in the specified area in the last cell.

The notebook will create a directory named `wolf-or-husky`, download the necessary images, and train the model.

