# AI07-Heart-Disease

## 1. Overview
Ther purpose of this project is to predict the presence of heart disease in a patients. This project use the dataset from https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset and was created using Google Colab. The framewok used is Pandas, Scikit-learn and TensorFlow Keras. 

## 2. Methodology
### Data preprocessing
The data is in .csv form and was saved in Google Drive before it was loaded to the Google Colab. The data was cleaned by removeing unwanted features, all categorical variable and label was encoded and splitted into train and test set with the ratio of 70 -30

### Model
The classification problem was handled by using the feedfoward neural network. The structure of the model is  ![Annotation 2022-08-01 025024](https://user-images.githubusercontent.com/92585515/182041669-c9c30f5d-f52f-4cc0-8b28-d65318a60c5e.jpg)

Model is then trained with batch size pf 32 in 300 epochs. Training stops at epoch 300 and obtain accuracy of 95.4% with validation accuracy of 95.4%.

![Annotation 2022-08-01 025025 jpg](https://user-images.githubusercontent.com/92585515/182042089-0cd415ad-be17-4e2a-81a6-f110fcf946fb.png)
![download (1)](https://user-images.githubusercontent.com/92585515/182042129-f2cc7ac7-829f-490e-b475-9599d82be502.png)
![download](https://user-images.githubusercontent.com/92585515/182042132-96ddc516-b7dc-4126-8746-010d5e138e6f.png)
