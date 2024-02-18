# COVID-19 X-ray Detection CNN Model

## Overview

This project explores the use of TensorFlow to develop a Convolutional Neural Network (CNN) model to detect COVID-19 infection in X-ray images. The model is trained to classify X-ray images into two categories: normal and infected with COVID-19. 

## Dataset

The dataset used in this project is available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset?resource=download). It includes X-ray images of patients with COVID-19 as well as normal cases.
An additional validation dataset was created by taking batches from the training dataset.

## File Structure

.  
├── README.md  
├── requirements.txt  
├── cnn-classifier-pipeline.ipynb  
├── data  
│ ├── test  
│ │ ├── covid_test_boston.jpeg  
│ │ ├── princeton_covid.jpg  
│ │ └── radiopedia_normal.jpg  
├── models  
│ └── covid19_xray_detection_model.h5  
├── logs  
│ ├── train   
│ │ ├── events.out.tfevents.1708282339.0.v2  
│ ├── validation  
│ │ ├── events.out.tfevents.1708282366.1.v2  
└── .gitignore

## Requirements

- Python 3.x
- Numpy
- Matplotlib
- OpenCV
- TensorFlow
- Keras

## Usage

To use this project, you can follow the following steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/camilababo/CNN-image-classifier
    ```

2. Navigate to the project directory:

    ```bash
    cd CNN-image-classifier
    ```

3. Install the required dependencies using pip and the provided requirements.txt file:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the provided Jupyter Notebook, `cnn-classifier-pipeline.ipynb`, using Jupyter and run the pipeline.


5. The trained model file is also available in `models/covid19_xray_detection_model.h5`.

