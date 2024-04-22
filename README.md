# Concordia University - COMP6721:Applied Artificial Intelligence - Winter 2024 

## Group J Project - Classification of Fashion Products using CNN 

This project is part of the coursework for the COMP 6721 - Applied Artificial Intelligence course at Concordia University for the Winter Term of 2024.
    
## About

This project aims to do a comparative study of CNN models like VGG16, ResNet18, and MobileNetV2 and evaluate the models on three datasets based on performance metrics. To achieve this we have taken up the problem of image classification in the Fashion Industry. With the increasing use of online shopping for clothing, it has become important for e-commerce websites to correctly identify categories for all the clothing items available on the website. To train the image classification models we use three different datasets, each consisting of 12k, 20k, and 40k images respectively.

## How-To

This repository consists of three .ipynb files each belonging to one of the three chosen datasets.

1) [Fashion Products Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small/data)
2) [Indo-Fashion Dataset](https://www.kaggle.com/datasets/validmodel/indo-fashion-dataset/data)
3) [Fashion Patterns Dataset](https://www.kaggle.com/datasets/nitinsss/fashion-dataset-with-over-15000-labelled-images/data) 

To obtain the datasets from Kaggle you can either download them in the form of a zip file and plug it into the notebook (or) download it directly into the Colab environment using the Kaggle API (commands for which are available in the notebooks). To access the API, create an access token from your Kaggle account.

Step 1: Sign in to your Kaggle Account

Step 2: Click on your profile badge and go to settings

Step 3: In the API tab, click on create a new token

Step 4: Your API token will be downloaded in the form of a JSON file named <I> kaggle.json </I>

Step 5: Upload the <I> kaggle.json </I> file to the Colab environment and run the cell with the Kaggle command to fetch the dataset.

Follow the below instructions to run and validate the models

<hr>

### Dataset - 1 (Fashion Products Images Small)

Step 1: Upload your <I> kaggle.json </I> file to the colab environment and collect the dataset

Step 2: Run the Data loading and training loop to obtain the model.

Step 3: Upload the 'Fashion_Products_Small.zip' file to the colab environment. Unzip the file by running <code> !unzip 'Fashion_Products_Small.zip' </code>

Step 4: Copy the path to the extracted folder and replace it in place of the existing dataset folder.

Step 5: Continue to run the notebook to validate the model.

<hr>

### Dataset - 2 (Indo-Fashion)

Step 1: Upload your <I> kaggle.json </I> file to the colab environment and collect the dataset

Step 2: Upload the 'Indo_Fashion_Dataset.csv' file to the colab environment and copy the path of the CSV file

Step 3: Replace the path string in place of 'pruned_test_data.csv' in the 'Data Loading' Subsection. 

Step 4: Continue to run the notebook to validate the model.

<hr>

### Dataset - 3 (Fashion Patterns)

Step 1: Upload your <I> kaggle.json </I> file to the colab environment and collect the dataset

Step 2: Run the Data loading and training loop to obtain the model.

Step 3: Upload the 'Fashion_Patterns_Dataset.zip' file to the colab environment. Copy the path of the zip file and place it in the 'zip_path' variable.

Step 4: The images will be extracted to a folder called '/content/temp3/'

Step 5: Continue to run the notebook to validate the model.
