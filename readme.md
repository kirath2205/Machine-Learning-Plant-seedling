Readme

1. Inception resent notebook - inception_resnet_final_notebook.ipynb
2. submission for inception resnet - inception-resnet.csv
3. vgg16 notebook - vgg16_notebook_final.ipynb
4. vgg16 submission - vgg16.csv
5. KNN notebook - KNN.ipynb
6. KNN submission - knn.csv
7. SVC notebook - SVC.ipynb
8. SVC submission - svc.csv
9. Exploratory Data Analysis notebook - Plant_Seedlings_Exploratory_Data_Analysis.ipynb


# Kaggle - Plant Seedling Classification
> CZ/CE 4041 Machine Learning \
> School of Computer Science and Engineering \
> Nanyang Technological University, Singapore

This GitHub repository contains both the code (Jupyter Notebooks) and submissions (CSV Files) for the [Kaggle Plant Seedling Classification Challenge](https://www.kaggle.com/c/plant-seedlings-classification). 

## Methodologies

###Creating directory structure
1. Mount your google drive and upload the train and test zip files on your google drive.
2. Run the Plant_Seedling_Exploratory_Data_Analysis.ipynb to generate the requiste directory structure

### Approach 1: kNN
> Navigate to `KNN.ipynb`

1. Run cells 1-10 to download the data from Kaggle and create seperate folders for training, validation and testing. 
2. Run the subsequent cells for model training
3. Download the csv file generated for submission


### Approach 2: Support Vector Machine
> Navigate to `SVC.ipynb`

1. Run cells 1-10 to download the data from Kaggle and create seperate folders for training, validation and testing. 
2. Run the subsequent cells for model training
3. Download the csv file generated for submission

### Approach 3: VGG-16
> Navigate to `vgg_16_notebook_final.ipynb`

1. Download the unzipped train and test folders to Documents/
2. Connect your google colab instance to localhost by making use of jupyter_http_over_ws to connect to localhost.
3. Run all cells to generate the folder for the best model weights as well as the csv file containing the predictions for the kaggle's test dataset.

VGG-16 was published in the paper "Very Deep Convolution Networks for Large-Scale image-recognition by Karen Simonyan and Andrew Zisserman, available at [arXiv](https://arxiv.org/pdf/1409.1556.pdf).

### Approach 4: Inception Resnet v2
> Navigate to `inception_resnet_final_notebook.ipynb`

1. Download the unzipped train and test folders to Documents/
2. Connect your google colab instance to localhost by making use of jupyter_http_over_ws to connect to localhost.
3. Run all cells to generate the folder for the best model weights as well as the csv file containing the predictions for the kaggle's test dataset. 

Inception Resnet v2 was published in the paper 'Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning', by Christian Szegedy, Sergey Ioffe, Vincent Vanhoucke, Alex Alemi, available at [arXiv](https://arxiv.org/abs/1602.07261). It is used as a transfer learning methodology via a Keras API documented [here](https://keras.io/api/applications/inceptionresnetv2/). 

## Authors

* Kirath Singh
* Pramurta Chatterjee
* Shashwat Arya
