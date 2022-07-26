# Melanoma Detection Assignment
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

1.Actinic keratosis
2.Basal cell carcinoma
3.Dermatofibroma
4.Melanoma
5.Nevus
6.Pigmented benign keratosis
7.Seborrheic keratosis
8.Squamous cell carcinoma
9.Vascular lesion

## Project Pipeline
Data Reading/Data Understanding 
Dataset Creation
Dataset visualisation 
Model Building & training : 
Created a CNN model, which could accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
Choosing an appropriate optimiser and loss function for model training
Training the model for ~20 epochs


Chosing an appropriate data augmentation strategy to resolve underfitting/overfitting 
Model Building & training on the augmented data :
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choosing an appropriate optimiser and loss function for model training
Training the model for ~20 epochs

Class distribution

Handling class imbalances: Rectifying class imbalances present in the training dataset with Augmentor library.
Model Building & training on the rectified class imbalance data 
Training the model for ~30 epochs

## Technologies Used
- python - version 3.0

## Contact
Created by [@SaxenaAnirudh] - feel free to contact me!
