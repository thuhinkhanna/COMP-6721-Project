# Concordia University - COMP6721:Applied Artificial Intelligence - Winter 2024 

## Group J Project - Classification of Fashion Products using CNN 

This project is part of the coursework for the COMP 6721 - Applied Artificial Intelligence course at Concordia University for the Winter Term of 2024.
    
## About

This project aims to do a comparative study of CNN models like VGG16, ResNet18, and MobileNetV2 and evaluate the models on three datasets based on performance metrics. 
To achieve this we have taken up the problem of image classification in the Fashion Industry. With the increasing use of online shopping for clothing, it has become important for e-commerce websites to correctly identify categories for all the clothing items available on the website.
To train the image classification models we use three different datasets, each consisting of 12k, 20k, and 40k images respectively.

## How-To

This repository consists of three .ipynb files each belonging to one of the three chosen datasets.

1) Fashion Products Images Dataset [link to dataset] (https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small/data)
2) Indo-Fashion Dataset [link to dataset] (https://www.kaggle.com/datasets/validmodel/indo-fashion-dataset/data)
3) Fashion Patterns Dataset [link to dataset] (https://www.kaggle.com/datasets/nitinsss/fashion-dataset-with-over-15000-labelled-images/data) 

Follow the below instructions to run and validate the models

### Dataset - 1 (Fashion Products Images Small)



### Dataset - 2 (Indo-Fashion)



### Dataset - 3 (Fashion Patterns)

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








