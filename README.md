# Concordia Univeristy-COMP6721:Applied Artificial Intelligence - Winter 2024 

## Group J Project- Classification of Fashion Products using CNN 

This project is part of the coursework for the COMP 6721 - Applied Artificial Intelligence course at Concordia University for the winter semester of 2024.
    
## About

This project aims to do comparative study of CNN models like resnet18, vgg16 and mobilenet and evaluate the model for chosen datasets based on their performance. 
To achieve this we have taken the need of image classification in fashion industry. With the increasing use of online shopping for clothing, it has become important for e-commerce websites to correctly identify categories for all the clothing items available on the website.
We have used three different datasets, each consisting of 12k, 20k and 40k images respectively.

## Repo Details & Installation

This repo consists of three different .ipynb files each belongs to one of the three chosen dataset.

To run these files there are some prequisities.

- Download your kaggle API token file and place it in the local directory to run these three python notebooks(scripts are available for downloading the datasets).

## Instructions to run the sample data sets

- ### Dataset -3
Unzip the downloaded images

import io
from torchvision.io import read_image
import zipfile

zip_path = 'REPLACE_THE_PATH_OF_SAMPLE_DATASET_HERE'

extracted_dir = 'temp3'

try:
    # Extract the zip file into the specified directory
    with zipfile.ZipFile(zip_path, 'r') as zip_ref:
        zip_ref.extractall(extracted_dir)
    print("Extraction successful.")
except Exception as e:
    print("Error occurred during extraction:", str(e))






