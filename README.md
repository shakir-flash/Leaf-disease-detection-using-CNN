# Leaf-disease-detection-using-CNN
Project to detect type of leaf disease and provide recommendation using Convolutional Neural Networks.

## Dataset
The dataset for this project can be downloaded from:\
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

The dataset is divided into three parts as follows:  

train - 70,295 images divided into 38 classes with 1,642 to 2,022 images per class.\
valid - 17,572 images divided into 38 classes with 410 to 505 images per class.\
test - 33 images (These images are not divided into their respective classes but the class can be inferred from the image filename)\

## Requisite
System requisite:
Hardware:
1. System : Intel core i5 2.7 GHz.
2. Hard Disk : 250 GB.
3. Ram : 8 GB

The external libraries required for running Train.ipynb are:
1. Numpy, CV2
2. Pandas
3. Scipy
4. Matplotlib
5. Sklearn/scikit-learn
6. Tensorflow (Version 2.3.0 or higher preferred), TFlearn

## Model

The different layers used in this model are as follows:

Input\
Pre-processing\
Segmentation\
Feature extraction: Input, Convolutional Layer, ReLu layer, pooling layer, FC layer \
Neural Network classification

## Structure

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/307a8ca9-65c3-46af-bdbd-34929294b840)

## Epoch vs Accuracy and loss

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/dcdde200-de5a-4577-bbc0-d17234be9869)   

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/1e3a2abc-8234-405c-926f-3e4a822afc96)   

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/06f271d9-03b9-4bec-9f11-d1d3c17a3d9c)

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/c560fdea-f8af-4198-ac57-8b63177b4585)   

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/8ffce665-cb71-40b7-a4b6-44830b6c95f6)

## Outputs

Generated output is in the form of a UI, which shows the details of leaf disease, and recommendation for the type of disease.

Healthy leaf:

![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/07fe59cf-10e5-467f-910e-8e25da14217c)


Diseased leaves:\
![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/bce6fcf1-bf8f-4376-b28f-c2d398ba77de)


![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/eb67456a-dcda-455a-9917-7601fb6eb4e1)


![image](https://github.com/shakir-flash/Leaf-disease-detection-using-CNN/assets/59859522/b50efc7a-2d92-4e1d-8619-d0bacac7d572)




















